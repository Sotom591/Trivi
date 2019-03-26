<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled>
        <b>Trivi</b>
      </b-nav-item>
      <b-nav-item disabled>Correct: {{ numCorrect }}/{{ total }}</b-nav-item>
    </b-nav>
  </div>
</template>
<script>
export default {
  props: ['numCorrect', 'total']
}
</script>

