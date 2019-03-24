<template>
  <div class="question-box-cont">
    <b-jumbotron>
      <template slot="lead">{{currentQu.question}}</template>

      <hr class="my-4">

      <p>Answers Here</p>

      <b-button variant="primary" href="#">Submit</b-button>
      <b-button variant="success" href="#">Next</b-button>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  props: {
    currentQu: Object
  }
}
</script>
