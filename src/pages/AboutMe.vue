<template>
    <div class="q-pa-md row items-start q-gutter-md">
        <q-card class="my-card text-white" style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)">
            <q-card-section>
                <div class="text-h6">Our Changing Planet</div>
                <div class="text-subtitle2">by John Doe</div>
            </q-card-section>
            <q-card-section class="q-pt-none">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </q-card-section>
        </q-card>
        <q-card class="my-card">
            <q-card-section horizontal>
                <q-img class="col-5" src="https://cdn.quasar.dev/img/parallax1.jpg" />

                <q-card-section>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                </q-card-section>
            </q-card-section>

            <q-separator />

            <q-card-actions>
                <q-btn flat round icon="event" />
                <q-btn flat>
                    5:30PM
                </q-btn>
                <q-btn flat>
                    7:00PM
                </q-btn>
                <q-btn flat color="primary">
                    Reserve
                </q-btn>
            </q-card-actions>
        </q-card>
    </div>

    <q-page padding>
        <!-- content -->
        <q-card-section>
            Hello world!
        </q-card-section>
        <q-btn color="primary" icon="home" label="Go Home" @click="$router.replace('/')" />
    </q-page>
</template>

<script>
export default {
  // name: 'PageName',
}
</script>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 300px
</style>
