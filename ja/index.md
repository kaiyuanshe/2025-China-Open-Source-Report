---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "2025 中国オープンソース年次報告書"
  text: ""
  tagline: "日本語版は現在準備中です。"
  actions:
    - theme: brand
      text: 日本語版を読む
      link: /ja/preface
    - theme: alt
      text: 過去の年次報告書
      link: https://kaiyuanshe.feishu.cn/wiki/wikcnUDeVll6PNzw900yPV71Sxd
---

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers,
  VPTeamPageSection
} from 'vitepress/theme'

const japaneseTranslationMembers = [
  {
    avatar: 'https://avatars.githubusercontent.com/u/1667148?v=4',
    name: '高須正和 / TAKASU Masakazu',
    title: '日本語版 主翻訳・校閲・保守',
    links: [
      { icon: 'github', link: 'https://github.com/takasumasakazu' },
      { icon: 'link', link: 'https://takasumasakazu.net/' }
    ],
  },
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>日本語版翻訳チーム</template>
    <template #lead>
      2025 中国オープンソース年度報告 日本語版の翻訳・校閲・保守に関わるメンバーです。
    </template>
  </VPTeamPageTitle>

  <VPTeamPageSection>
    <template #title>翻訳・レビュー・保守</template>
    <template #members>
      <VPTeamMembers size="small" :members="japaneseTranslationMembers" />
    </template>
  </VPTeamPageSection>
</VPTeamPage>
