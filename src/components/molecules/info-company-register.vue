<template>
  <b-row class="text-center">
    <b-col  class="text-left">
      <div class="company-icon">
        <span style="color: #E23444;">
          <i class="fas fa-building fa-2x"></i>
        </span>
      </div>
    </b-col>
    <b-col class="text-left" cols="11" md="11" sm="12">
      <div class="company-info">
        <h1>Criar Empresa</h1>
        <h4>Olá! Nessa sessão iremos criar e cadastrar uma nova empresa</h4>
      </div>
    </b-col>
  </b-row>
</template>

<script>
export default {};
</script>

<style>
.company-icon i {
  margin-top: 5px;
}
.company-info {
  transform: translateX(-60px);
}
.company-info h1 {
  color: #20253a;
}
.company-info h4 {
  color: #5a5d6e;
}

@media only screen and (max-width: 1200px) {
  .company-info {
  transform: translateX(0px);
}
}

</style>