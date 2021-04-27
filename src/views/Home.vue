<template>
  <Hero />
  <div class="container">
    <Section>
      <ContentBlock />
    </Section>
    <Section>
      <div class="row">
        <div class="col">
          <Carousel />
        </div>
      </div>
    </Section>
    <Section>
      <div class="row">
        <div class="col-3">
          <Card />
        </div>
        <div class="col-3">
          <Card />
        </div>
        <div class="col-3">
          <Card />
        </div>
        <div class="col-3">
          <Card />
        </div>
      </div>
    </Section>
    <Section>
      <div class="row">
        <div class="col">
          <div class="py-5 text-center bg-primary">
            <p class="h3">Click Me!</p>
            <a href="#" class="btn btn-lg btn-secondary">Button</a>
          </div>
        </div>
      </div>
    </Section>
  </div>
</template>

<script>
import Carousel from "@/components/Carousel";
import ContentBlock from "@/components/ContentBlock";
import Section from "@/components/Section";
import Card from "@/components/Card";
import Hero from "@/components/Hero";
export default {
  name: "Home",
  components: {
    Carousel,
    ContentBlock,
    Section,
    Card,
    Hero,
  },
};
</script>
