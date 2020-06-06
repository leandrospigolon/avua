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
  <div class="q-pa-md">   
    <div class="row">
      <div class="col">
        <div class="q-pa-md row items-start q-gutter-md">
            <q-card class="my-card">
              <img src="~assets/efra.png"
              style="width:60vw;max-width:300px;"
              >
              <q-card-section>
                <div class="text-h6">Sou o Efra</div>
                <div class="text-subtitle2">Tradutor</div>
              </q-card-section>

              <q-card-section class="q-pt-none">
              </q-card-section>
            </q-card>
          </div>
      </div>

      <div class="col">
      <div class="q-pa-md row items-start q-gutter-md">
            <q-card class="my-card">
              <img src="~assets/stefanie.png"
              style="width:30vw;max-width:283px;"
              >

              <q-card-section>
                <div class="text-h6">Sou a Stefanie</div>
                <div class="text-subtitle2">Interpreti</div>
              </q-card-section>

              <q-card-section class="q-pt-none">
              </q-card-section>
            </q-card>
          </div>
      </div>
      <div class="col">
      <div class="q-pa-md row items-start q-gutter-md">
            <q-card class="my-card">
              <img src="~assets/valquiria.png"
              style="width:30vw;max-width:294px;"
              >

              <q-card-section>
                <div class="text-h6">Olá, sou a Valquiria</div>
                <div class="text-subtitle2">Interpreti</div>
              </q-card-section>

              <q-card-section class="q-pt-none">
              </q-card-section>
            </q-card>
          </div>
      </div>
    </div>
  </div>
  </q-page>
</template>