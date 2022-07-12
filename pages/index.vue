<template>
  <div>
    <b-img src="https://images.unsplash.com/photo-1560448205-4d9b3e6bb6db?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80" fluid alt="Responsive image" />
    <div class="container text-front">
      <h5>Alterstay is a digital hospitality ecosystem where we envision an always-improving experience for all hospitality stakeholder. We are dedicated for a different and better guest experience, owning experience, and team working experience, through continuous improvement and digitalization.Alterstay: Experience Different</h5>
      <b-button href="#" variant="light">
        Property Search
      </b-button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
  .text-front{
    padding-top: 25%;
    padding-left: 50%;
  z-index: 1;
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

@media only screen and (max-width: 768x) {
  .text-front {
     z-index: 1;
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  }
}
</style>
