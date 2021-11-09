<template name="component-name">
  <!-- Desktop -->
  <div class="d-none d-md-block">
    <div class="row mt-4">
      <div class="col-md-6">
        <div class="d-flex h-100">
          <div class="justify-content-center align-self-center">
            <h2><strong>Delicious food menu,</strong><br />in your gadget</h2>
            <p>Ayo segera pilih makanan favorit anda!</p>
            <button type="button" class="btn btn-dark">Pesan</button>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <img src="../assets/breakfast.svg" alt="breakfast" width="500" />
      </div>
    </div>
  </div>

  <!-- Mobile -->
  <div class="d-sm-block d-md-none">
    <div class="row mt-4">
      <div class="col-md-6">
        <div class="d-flex h-100">
          <div class="justify-content-center align-self-center">
            <h2><strong>Delicious food menu,</strong><br />in your gadget</h2>
            <p>Ayo segera pilih makanan favorit anda!</p>
            <button type="button" class="btn btn-dark">Pesan</button>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <img src="../assets/breakfast.svg" alt="breakfast" width="500" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
.btn-dark {
  color: #fff;
  background-color: #6c63ff;
  border-color: #6c63ff;
}
</style>