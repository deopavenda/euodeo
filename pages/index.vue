<template>
  <div>
    <Navbar />
    <HeroSection />
    <AboutSection />
    <ProjectsSection />
    <ContactSection />
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';
import NavbarSection from '~/components/Navbar.vue';

export default {
  components: {
    HeroSection,
    AboutSection,
    ProjectsSection,
    ContactSection,
    NavbarSection
  }
}
</script>./Index.vue
