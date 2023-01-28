<template>
  <div id="app">
    <Form @submit="onSubmit">
      <Field name="email" type="email" />
      <button>Sign up for newsletter</button>
    </Form>
  </div>
</template>
<script>
import { Form, Field } from 'vee-validate';
export default {
  components: {
    Form,
    Field,
  },
  methods: {
    onSubmit() {
      console.log('Submitting :(');
    },
  },
};
</script>

<style>

</style>
