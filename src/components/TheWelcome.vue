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
    <template #heading>About</template>

    Ngos's
    <a href="https://vuejs.org/" target="_blank" rel="noopener">official blog</a>
    provides you some aspects of my thought. Please note that this is just the introduction
    web for my blog (actually for my trying to deploy my very first website :))
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Technology</template>

    The project blog (not in this website) is served with RestAPI by NodeJS, Express
    <br>
    The client is built with Vue.js
    <br />

    More information is available at <code> <a href="https://github.com/dat02092k1">github</a> </code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Author</template>
    As an (trying to be) independent man and just a learner and beginner, I'm normal guy stuck with these fucking
    stuff in this life and just try to figure life out.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

   Will try to buil form FAQ later if i can :)
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Buy me a coffee!</template>
    MB Bank: 46456886868
    <br>
    Ngo Quoc Dat
  </WelcomeItem>
</template>
