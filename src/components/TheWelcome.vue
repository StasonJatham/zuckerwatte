<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Blog</template>

    Check out our blog to read about our customer success stories.
    <a class="red" target="_blank" href="https://vuejs.org/">And our own, of course.</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>
    Modern tools, make you fast and save you time. In a world where time is 
    money and much more important time is time, this will save you big on the most important 
    resource there is. Let's build together!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

    Most consulting companies focus on a multi-cloud startegy and this is awesome,
    get the best from every cloud. We focus our expertise on AWS and CloudFlare in order 
    to bring you the most sustainable value from those platforms. We'd rather support fewer 
    providers, that way we can master them!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Support</template>

    Got stuck? Have a question? No matter where you are in your project, be it at the beginning,
    in the middle, at the end doing some finetuning, or maybe you just woke up this
    morning with the next big thing on your mind: Let's make it happen &#128079;!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Us</template>

    As a new company, we really need your feedback to be better and grow. Thank 
    you in advance!
    <a target="_blank" href="https://vuejs.org/sponsor/">Submit some feedback</a>.
  </WelcomeItem>
</template>
