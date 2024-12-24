<script setup>
import { RouterLink } from 'vue-router';
import { VsxIcon } from 'vue-iconsax';
</script>

<template>
<section>
      <div class="container m-auto py-6 px-6">
        <RouterLink
          to="/jobs"
          class="text-green-500 hover:text-green-600 flex items-center"
        >
        <VsxIcon iconName="ArrowCircleLeft2" size="20" type="linear" class="mr-3"/> Back to Job Listings
        </RouterLink>
      </div>
    </section>
</template>