<template>
  <div>
    <header-part></header-part>
    <account-part></account-part>
    <contact-part></contact-part>
    <footer-part></footer-part>
  </div>
</template>

<script>
import HeaderPart from "@/components/header2.vue";
import AccountPart from "@/components/account.vue";
import ContactPart from "@/components/contact.vue";
import FooterPart from '@/components/footer.vue';
export default {
  components: { HeaderPart, AccountPart, ContactPart, FooterPart }
};
</script>

<style scoped>
</style>
