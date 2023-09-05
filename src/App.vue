<template>
  <div>
    <section class="main-section">
      <div class="container-app">
        <div class="main d-flex align-items-start">
          <div class="main-tab nav flex-column nav-pills me-3" id="v-pills-tab" role="tablist"
            aria-orientation="vertical">
            <div class="nav-link active" id="v-pills-home-tab" data-bs-toggle="pill" data-bs-target="#v-pills-home"
              type="button" role="tab" aria-controls="v-pills-home" aria-selected="true">
              <span>1</span>
              <div>
                <p>Step 1</p>
                <p>YOUR INFO</p>
              </div>
            </div>
            <div class="nav-link" id="v-pills-profile-tab" data-bs-toggle="pill" data-bs-target="#v-pills-profile"
              type="button" role="tab" aria-controls="v-pills-profile" aria-selected="false"><span>2</span>
              <div>
                <p>Step 2</p>
                <p>YOUR INFO</p>
              </div>
            </div>
            <div class="nav-link" id="v-pills-messages-tab" data-bs-toggle="pill" data-bs-target="#v-pills-messages"
              type="button" role="tab" aria-controls="v-pills-messages" aria-selected="false"><span>3</span>
              <div>
                <p>Step 3</p>
                <p>YOUR INFO</p>
              </div>
            </div>
            <div class="nav-link" id="v-pills-settings-tab" data-bs-toggle="pill" data-bs-target="#v-pills-settings"
              type="button" role="tab" aria-controls="v-pills-settings" aria-selected="false"><span>4</span>
              <div>
                <p>Step 4</p>
                <p>YOUR INFO</p>
              </div>
            </div>
          </div>
          <div class="main-form tab-content" id="v-pills-tabContent">
            <div class="tab-pane fade show active" id="v-pills-home" role="tabpanel" aria-labelledby="v-pills-home-tab">
              ...</div>
            <div class="tab-pane fade" id="v-pills-profile" role="tabpanel" aria-labelledby="v-pills-profile-tab">...
            </div>
            <div class="tab-pane fade" id="v-pills-messages" role="tabpanel" aria-labelledby="v-pills-messages-tab">...
            </div>
            <div class="tab-pane fade" id="v-pills-settings" role="tabpanel" aria-labelledby="v-pills-settings-tab">...
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
.main-section {
  display: flex;
  width: 100%;
  height: 100vh;
}

.main {
  width: 1000px;
  height: 600px;
  background-color: #fff;
  border-radius: 15px;
  padding: 10px;

  &-tab {
    width: 30%;
    height: 100%;
    border: 1px dashed blue;
    border-radius: 10px;
    background-color: #483eff;
  }

  &-form {
    width: 70%;
    height: 100%;
    border: 1px dashed red;
    border-radius: 10px;
    padding: 20px 60px;
  }
}
</style>