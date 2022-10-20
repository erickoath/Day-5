<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <h1>Project</h1>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Automatic Sheet Metal Press Brake</template>
    Project Magang bersertifikat dari Kampus Merdeka di PT Stechoq Robotika Indonesia
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Drone Sebagai Media Pembelajaran</template>
    Sebuah project yang menggunakan drone untuk media Pembelajaran. Project ini dilaksanakan pada pondok Pesantren dengan melibatkan murid kelas IX dan kelas X.

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengiriman Barang Berbasis UAV</template>
    Sebuah project yang dilaksanakan dalam rangka mengikuti lomba KRTI (Kontes Robot Terbang Indonesia) pada Tahun 2020. 
    Dengan menggunakan Quadcopter sebagai transportasi dan QR Code sebagai penanda lokasi
  </WelcomeItem>

</template>
