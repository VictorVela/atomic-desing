<template>
  <b-container>
    <InfoComapanyRegister />
    <b-row class="d-flex justify-content-between mt-4">
      <CardInputMd input_title="Card1" placeholderValue="test" />
      <CardInputMd input_title="Card2" placeholderValue="test" />
    </b-row>
    <b-row class="d-flex justify-content-between mt-4">
      <b-col cols="6" md="12" sm="12">
        <CardInputMd input_title="Card1" placeholderValue="test" />
      </b-col>
      <b-col cols="6" md="12" sm="12">
        <CardInputMd input_title="Card2" placeholderValue="test" />
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import CardInputMd from "../molecules/card-input-md";
import InfoComapanyRegister from "../molecules/info-company-register";

export default {
  name: "App",
  components: {
    CardInputMd,
    InfoComapanyRegister,
  },
};
</script>

<style>
</style>