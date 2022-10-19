<template>
  <div class="contact">
    <h1>This is a contact page</h1>
    <ContactForm :value="value"/>
  </div>
</template>


<script>
import ContactForm from "@/components/ContactForm.vue";
export default {
  name: "Contact",
  components: {
    ContactForm
  },
    data() {
    return {
      value: 10
    }
  }
}
</script>