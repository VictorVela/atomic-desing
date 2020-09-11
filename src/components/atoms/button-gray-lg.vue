<template>
  <div class="button-gray-lg">
    <input type="submit" name="" value="Login">
  </div>
</template>

<script>
export default {

}
</script>

<style>
.button-gray-lg input[type = "submit"]{
  border:0;
  background: none;
  display: block;
  text-align: center;
  border: 2px solid #808182;
  padding: 10px 100px;
  outline: none;
  color: white;
  border-radius: 10px;
  transition: 0.25s;
  cursor: pointer;
}

.button-gray-lg input[type = "submit"]:hover{
  background: #808182;
}
</style>