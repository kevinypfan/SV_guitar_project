<template>
  <div>
    <Carousels />
    <PhotoBlocks />
    <PersonalProfile />
    <DummyBlock />
    <Dummytitle />
    <ArticleBlocks />
  </div>
</template>

<script>
import Carousels from '~/components/Carousels'
import PhotoBlocks from '~/components/index/PhotoBlocks'
import PersonalProfile from '~/components/index/PersonalProfile'
import DummyBlock from '~/components/utils/DummyBlock'
import Dummytitle from '~/components/utils/Dummytitle'
import ArticleBlocks from '~/components/index/ArticleBlocks'
export default {
  components: {
    Carousels,
    PhotoBlocks,
    PersonalProfile,
    DummyBlock,
    Dummytitle,
    ArticleBlocks
  }
}
</script>

<style>
</style>
