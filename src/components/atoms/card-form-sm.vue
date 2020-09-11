<template>
  <div class="card-form-lg"></div>
</template>

<script>
export default {};
</script>

<style>
.card-form-lg {
  height: 40%;
  width: 40%;
  padding: 40px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: #ffffff;
  text-align: center;
  border-top: 8px solid red;
  border-bottom-left-radius: 10px;
  border-bottom-right-radius: 10px;

  box-shadow: 0 2.8px 2.2px rgba(0, 0, 0, 0.034),
    0 6.7px 5.3px rgba(0, 0, 0, 0.048), 0 12.5px 10px rgba(0, 0, 0, 0.06),
    0 22.3px 17.9px rgba(0, 0, 0, 0.072), 0 41.8px 33.4px rgba(0, 0, 0, 0.086),
    0 100px 80px rgba(0, 0, 0, 0.12);
}
</style>