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
      <q-card class="my-card">
      <q-video src="https://www.youtube.com/embed/yncRzJvRJgI" />

      <q-card-section>
        <div class="text-h6">Musica, Poesia e Linguagem por Sinais</div>
        <div class="text-subtitle2">Avua Libras</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        Somos profissionais Tradutores e Intérpretes de Libras. Através desse projeto, vamos compartilhar com você nossas experiências profissionais, no ambiente artístico, e mostrar como é possível fazer construções poéticas que misturam a língua de sinais, o corpo e edição de vídeo.
      </q-card-section>
    </q-card>
    <div class="q-pa-md">
      <p>
        <img
        src="~assets/logo.png"
        style="width:30vw;max-width:150px;"
        >
      </p>
    </div>
  </div>
  </q-page>
</template>
<script>
export default {
  data () {
    return {
      left: false
    }
  }
}
</script>
