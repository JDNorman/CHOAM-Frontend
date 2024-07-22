<script setup>
import WelcomeItem from './WelcomeItem.vue'
import AboutIcon from './icons/IconAbout.vue'
import CreditsIcon from './icons/IconCredits.vue'
import ServicesIcon from './icons/IconServices.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import DiscordIcon from './icons/IconDiscord.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <AboutIcon />
    </template>
    <template #heading><span class="yellow-hover">About</span></template>

    This website is the web terminal for interacting CHOAM's services, 
    including a map service, a market hub service, and server organization.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CreditsIcon />
    </template>
    <template #heading><span class="yellow-hover">Credits</span></template>

    Credit for this project goes to: 
    
    <br /> 
    
    <img src="https://cdn.discordapp.com/guilds/1215140184446738472/users/1013147665325883463/avatars/3400db2888da4fbf325727f899326ee9.png" 
    class="inline w-4 rounded-full"/> 
    <span class="text-purple"> Malamania</span>, 
    
    <img src="https://cdn.discordapp.com/avatars/720847074131968000/6e6f1dbb4ece883479b6754e6eda4823.png"
    class="inline w-4 rounded-full"> 
    <span class="text-purple"> TehNizZ (NZMPLAYS)</span>, 
    
    <img src="https://cdn.discordapp.com/avatars/187931402908598272/8be7a43bd3be59562733f9ab4778d9af.png"
    class="inline w-4 rounded-full">
    <span class="text-purple"> Halex</span>, 

    <img src="https://cdn.discordapp.com/avatars/209728362703355916/a_1438fe08c768ff2513a4bb6e61521e8b.gif"
    class="inline w-4 rounded-full">
    <span class="text-purple"> shib</span>, and 

    <img src="https://cdn.discordapp.com/avatars/164647838704205825/6ade09e8a47378b353ce57e22da1ca70.png"
    class="inline w-4 rounded-full">
    <span class="text-purple"> Jot</span>!    
  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DiscordIcon />
    </template>
    <template #heading><span class="yellow-hover">Bug Reports</span></template>
    
    Catch a bug? Please join 
    <a href="https://discord.gg/ND2MBzTetu">this server</a> 
    to report anything you may have caught! 
    
    <br />
    <br />
    
    If there are any requests you would like to make for new ideas or ways we could improve, 
    feel free to join the discord server to ask!

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ServicesIcon />
    </template>
    <template #heading>Services</template>

    We provide many services, including a world map, a market tracker, a taxi service, and much more!
    We are always looking for ways to improve, and we are constantly coming up with more ideas for our systems.
    Feel free to reach out anytime to talk to us if anything is wrong or if any of our services could be made better!

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Us</template>

    As an independent project, we relies on community backing for its sustainability. You can help
    us by
    <a href="https://ko-fi.com/animateobject_" target="_blank" rel="noopener">buying us a coffee</a>!

    Purchases will increase the benefits you get from joining our discord server, we provide more access into our testing channels
    as well as more unique benefits!
  </WelcomeItem>
</template>
