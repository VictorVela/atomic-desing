<template>
  <div class="card-input-md">
    <div class="card-input-title">
      <h3>{{ input_title }}</h3>
      <b-input id="inline-form-input-name" class="mb-2 mr-sm-2 mb-sm-4 mt-sm-4 mr-sm-4" :placeholder="placeholderValue"></b-input>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    input_title: String,
    placeholderValue: String,
  },
};
</script>

<style>
.card-input-md {
  width: 50%;
  background: #ffffff;
  border-radius: 10px;
  box-shadow: 0 2.8px 2.2px rgba(0, 0, 0, 0.034),
    0 6.7px 5.3px rgba(0, 0, 0, 0.048), 0 12.5px 10px rgba(0, 0, 0, 0.06),
    0 22.3px 17.9px rgba(0, 0, 0, 0.072), 0 41.8px 33.4px rgba(0, 0, 0, 0.086),
    0 100px 80px rgba(0, 0, 0, 0.12);
}

.card-input-title {
  text-align: left;
  padding: 20px;
}
</style>