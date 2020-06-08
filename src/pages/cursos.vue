<template>
  <q-page>
    <div class="q-pa-md">
      <div class="row">
        <div class="col=6">
          <q-tabs align="left">
            <q-route-tab to="/" label="INICIAL" />
            <q-route-tab to="/cursos" label="CURSOS" />
            <q-route-tab to="/trabalhos" label="NOSSOS TRABALHOS" />
          <q-route-tab to="/somos" label="QUEM SOMOS" />
      </q-tabs>
        </div>
      </div>
    </div>
    <div class="row">
    <div class="col">
    <div class="q-pa-md row items-start q-gutter-md">
    <q-card class="my-card" flat bordered>
      <q-card-section horizontal>
        <q-card-section class="q-pt-xs">
          <div class="text-overline">Curso</div>
          <div class="text-h5 q-mt-sm q-mb-xs">Libras para iniciantes</div>
          <div class="text-caption text-grey">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </div>
        </q-card-section>

        <q-card-section class="col-5 flex flex-center">
          <q-img
            class="rounded-borders"
            img src="~assets/simbolo.png"
            style="width:60vw;max-width:120px;"
          />
        </q-card-section>
      </q-card-section>

      <q-separator />

      <q-card-actions>
        <q-btn flat round icon="event" />
        <q-btn flat>
          7:30PM
        </q-btn>
        <q-btn flat color="primary">
          Reserve
        </q-btn>
      </q-card-actions>
    </q-card>
     </div>
     </div>

     <div class="col">
 <div class="q-pa-md row items-start q-gutter-md">
     <q-card class="my-card" flat bordered>
      <q-card-section horizontal>
        <q-card-section class="q-pt-xs">
          <div class="text-overline">Curso</div>
          <div class="text-h5 q-mt-sm q-mb-xs">Interprete avançado</div>
          <div class="text-caption text-grey">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </div>
        </q-card-section>

        <q-card-section class="col-5 flex flex-center">
          <q-img
            class="rounded-borders"
            img src="~assets/simbolo.png"
            style="width:60vw;max-width:120px;"
          />
        </q-card-section>
      </q-card-section>

      <q-separator />

      <q-card-actions>
        <q-btn flat round icon="event" />
        <q-btn flat>
          19:30PM
        </q-btn>
        <q-btn flat color="primary">
          Reserve
        </q-btn>
      </q-card-actions>
    </q-card>
     </div>
     </div>
     </div>
  </q-page>
</template>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 350px
</style>

<script>
export default {
  data () {
    return {
      lorem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'
    }
  }
}
</script>
