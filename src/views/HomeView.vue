<script setup lang="ts">
import Card from '@/components/Card.vue';
</script>

<template>
  <div class="home-view">
    <Card>
      <template #header>
        <h2>Who is Yelko?</h2>
      </template>
      <p>
        Founder and engineer who is proactive, curious, and detail-oriented with a proven ability to learn quickly. Skilled at analysing problems deeply and making informed decisions. Demonstrates leadership by taking responsibility and contributing innovative ideas. Values collaboration and mutual support as the most important qualities in colleagues and companies. 
      </p>
    </Card>
    <Card>
      <template #header>
        <h2>My top skills</h2>
      </template>
      <ul>
        <li>Startup Founding</li>
        <li>Software Development</li>
        <ul>
          <li>Java 6+ years</li>
          <li>Javascript/Typescript 6+ years</li>
          <li>Python 2+ years</li>
        </ul>
        <li>Technical Leadership</li>
        <li>Cloud Product Management</li>
        <li>Product Ownership</li>
        <li>Cross-functional Collaboration</li>
        <li>Hiring & Recruitment</li>
      </ul>
    </Card>
    <Card>
      <template #header>
        <h2>Contact</h2>
      </template>
      <p>
        Connect with me on 
        <a href="https://www.linkedin.com/in/yelk0/" target="_blank" rel="noopener noreferrer">LinkedIn</a>.
      </p>
    </Card>
  </div>
</template>
<style scoped lang="scss">
.home-view {
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

ul {
  list-style-type: disc;
  padding-left: 1.5rem;

  li {
    margin-bottom: 0.5rem;
    font-size: 1.2rem;
    color: #555;
  }
}
</style>
