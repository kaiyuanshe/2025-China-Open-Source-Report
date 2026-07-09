---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "2025 中国オープンソース年度報告"
  text: ""
  tagline: "開源社が複数の組織と共同で継続的に発表している、中国オープンソース産業に関する総合的な年次報告書"
  actions:
    - theme: brand
      text: 日本語版を読む
      link: /ja/preface
    - theme: alt
      text: 中国語版を読む
      link: /preface
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

features:
  - icon:
      src: "/image/home/KaiYuanShe-logo.png"
      width: 40
      height: 40
    title: 開源社
    details: 開源社（英語名 KAIYUANSHE）は2014年に設立された、オープンソースに貢献する個人ボランティアによるコミュニティです。「貢献・コンセンサス・共同統治」の原則に基づき、ベンダーニュートラル、公益、非営利の理念を保ちながら、健全で持続可能なオープンソース・エコシステムの共創を目指しています。
    link: https://kaiyuanshe.cn/
    linkText: 公式サイト
  - icon:
      src: "/image/home/x_lab2017_logo.jpg"
      width: 40
      height: 40
    title: X-lab 開放実験室
    details: X-lab 開放実験室は、国内外の大学、スタートアップ、IT企業などの専門家・研究者・エンジニアが参加する、オープンソース研究とイノベーションのための開かれた共同体です。オープンソース戦略、メトリクス、デジタル・エコシステムなどを継続的に研究し、オープンソース・コミュニティの測定、分析、データ活用に取り組んでいます。
    link: https://github.com/X-lab2017
    linkText: GitHub
---

<script setup>
import { withBase } from 'vitepress'
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers,
  VPTeamPageSection
} from 'vitepress/theme'

// 召集人
const convener = [
  {
    avatar: withBase('/image/home/avatar/王伟.jpg'),
    name: '王伟',
  },
]

// 巻頭言
const forewordMembers = [
  {
    avatar: withBase('/image/home/avatar/江波.jpg'),
    name: '江波',
  }
]

// アンケート編
const questionnaireDesignMembers = [
  {
    avatar: withBase('/image/home/avatar/谢思怡.jpg'),
    name: '谢思怡',
  },
]

// データ編
const dataPieceMembers = [
  {
    avatar: withBase('/image/home/avatar/韩凡宇.jpg'),
    name: '韩凡宇',
  },
  {
    avatar: withBase('/image/home/avatar/彭佳恒.jpg'),
    name: '彭佳恒',
  },
  {
    avatar: withBase('/image/home/avatar/张震.jpg'),
    name: '张震',
  },
  {
    avatar: withBase('/image/home/avatar/潘飞扬.jpg'),
    name: '潘飞扬',
  },
]

// 商業化編
const commercializationMembers = [
  {
    avatar: withBase('/image/home/avatar/袁滚滚.jpg'),
    name: '袁滚滚',
  },
]

// オープンソースAI編
const aiMembers = [
  {
    avatar: withBase('/image/home/avatar/李扬.jpg'),
    name: '李扬',
  },
  {
    avatar: withBase('/image/home/avatar/FeigeZhu.png'),
    name: '朱飞鸽',
  },
  {
    avatar: withBase('/image/home/avatar/夏小雅.jpg'),
    name: '夏小雅',
  },
  {
    avatar: withBase('/image/home/avatar/tedwang.jpg'),
    name: 'Ted Wang',
    title: '基礎インフラ部分',
  },
  {
    avatar: withBase('/image/home/avatar/tedwang.jpg'),
    name: '刘天栋',
  },
]

// オープンソースフィジカルAI編
const eiMembers = [
  {
    avatar: withBase('/image/home/avatar/江波.jpg'),
    name: '江波',
  },
  {
    avatar: withBase('/image/home/avatar/陈阳.jpg'),
    name: '陈阳',
  },
]

// Web3.0編
const web3Members = [
  {
    avatar: withBase('/image/home/avatar/ian-xu.png'),
    name: '许银 Ian Xu',
    title: 'Web3.0 基礎分析',
  },
  {
    avatar: withBase('/image/home/avatar/pseudoyu.jpg'),
    name: 'pseudoyu',
    title: 'Web3insight.ai データ支援',
  },
]

// オープンソースの主な出来事
const memorabiliaMembers = [
  {
    avatar: withBase('/image/home/avatar/庄表伟.jpg'),
    name: '庄表伟',
    title: '全体章',
  },
  {
    avatar: withBase('/image/home/avatar/梁尧.jpg'),
    name: '梁尧',
    title: '自動車分野のオープンソース',
  },
  {
    avatar: withBase('/image/home/avatar/李明康.jpg'),
    name: '李明康',
    title: 'オープンソース教育',
  },
]

// 翻訳チーム
const translations = [
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

// 全体取りまとめ・編集
const copyreaders = [
  {
    avatar: withBase('/image/home/avatar/庄表伟.jpg'),
    name: '庄表伟',
  },
  {
    avatar: withBase('/image/home/avatar/谢思怡.jpg'),
    name: '谢思怡',
  },
  {
    avatar: withBase('/image/home/avatar/李明康.jpg'),
    name: '李明康',
  },
]

// インフラ支援
const infrastructureMembers = [
  {
    avatar: withBase('/image/home/avatar/庄表伟.jpg'),
    name: '庄表伟',
  },
]

const japaneseEditionLinks = [
  { title: '巻頭言', link: '/ja/preface' },
  { title: 'オープンソースの主な出来事', link: '/ja/open-source-milestones' },
  { title: 'アンケート編', link: '/ja/questionnaire' },
  { title: 'データ編', link: '/ja/data' },
  { title: '商業化編', link: '/ja/commercialization' },
  { title: 'オープンソースAI編', link: '/ja/ossAI' },
  { title: 'オープンソースフィジカルAI編', link: '/ja/embodied-intelligence' },
  { title: 'Web3.0編', link: '/ja/web3' },
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>編纂チーム</template>
  </VPTeamPageTitle>

  <VPTeamPageSection v-if="convener">
    <template #title>召集人</template>
    <template #members>
      <VPTeamMembers size="small" :members="convener" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="forewordMembers">
    <template #title>巻頭言</template>
    <template #members>
      <VPTeamMembers size="small" :members="forewordMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="questionnaireDesignMembers">
    <template #title>アンケート編</template>
    <template #members>
      <VPTeamMembers size="small" :members="questionnaireDesignMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="dataPieceMembers">
    <template #title>データ編</template>
    <template #members>
      <VPTeamMembers size="small" :members="dataPieceMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="commercializationMembers">
    <template #title>商業化編</template>
    <template #members>
      <VPTeamMembers size="small" :members="commercializationMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="aiMembers">
    <template #title>オープンソースAI編</template>
    <template #members>
      <VPTeamMembers size="small" :members="aiMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="eiMembers">
    <template #title>オープンソースフィジカルAI編</template>
    <template #members>
      <VPTeamMembers size="small" :members="eiMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="web3Members">
    <template #title>Web3.0編</template>
    <template #members>
      <VPTeamMembers size="small" :members="web3Members" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="memorabiliaMembers">
    <template #title>オープンソースの主な出来事</template>
    <template #members>
      <VPTeamMembers size="small" :members="memorabiliaMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="translations">
    <template #title>日本語版翻訳チーム</template>
    <template #members>
      <VPTeamMembers size="small" :members="translations" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="copyreaders">
    <template #title>全体取りまとめ・編集</template>
    <template #members>
      <VPTeamMembers size="small" :members="copyreaders" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="infrastructureMembers">
    <template #title>インフラ支援</template>
    <template #members>
      <VPTeamMembers size="small" :members="infrastructureMembers" />
    </template>
  </VPTeamPageSection>
</VPTeamPage>

<VPTeamPageTitle>
  <template #title>日本語版を読む</template>
</VPTeamPageTitle>

<div class="ja-report-link-grid">
  <a
    v-for="item in japaneseEditionLinks"
    :key="item.link"
    class="ja-report-link-card"
    :href="withBase(item.link)"
  >
    {{ item.title }}
  </a>
</div>

<VPTeamPageTitle>
  <template #title>協作開源コミュニティ・団体</template>
</VPTeamPageTitle>

<div class="partner-logo-grid">
  <span class="partner-logo-card partner-logo-card-square">
    <img src="/image/home/KaiYuanShe-logo.png" alt="開源社"/>
  </span>
  <span class="partner-logo-card partner-logo-card-square">
    <img src="/image/home/x_lab2017_logo.jpg" alt="X-lab 開放実験室"/>
  </span>
  <span class="partner-logo-card partner-logo-card-wide">
    <img src="/image/home/logo-dark-FIT2CLOUD.svg" alt="FIT2CLOUD"/>
  </span>
  <span class="partner-logo-card partner-logo-card-wide">
    <img src="/image/home/KWDB.png" alt="KWDB"/>
  </span>
  <span class="partner-logo-card partner-logo-card-wide">
    <img src="/image/home/logo_gitee_light.png" alt="Gitee"/>
  </span>
  <span class="partner-logo-card partner-logo-card-wide">
    <img src="/image/home/openbuild-logo.svg" alt="OpenBuild"/>
  </span>
</div>

<VPTeamPageTitle>
  <template #title>協力メディア</template>
</VPTeamPageTitle>

<div class="partner-logo-grid partner-media-grid">
  <span class="partner-logo-card partner-logo-card-media">
    <img src="/image/home/csdn_logo.jpg" alt="CSDN"/>
  </span>
  <span class="partner-logo-card partner-logo-card-media">
    <img src="/image/home/sf_logo.png" alt="SegmentFault"/>
  </span>
</div>

<style>
.ja-report-link-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(160px, 1fr));
  gap: 14px;
  width: min(1040px, 100%);
  margin: 0 auto 40px;
  padding: 0 24px;
}

.ja-report-link-card {
  display: flex;
  align-items: center;
  min-height: 56px;
  padding: 14px 16px;
  border: 1px solid rgba(148, 163, 184, 0.22);
  border-radius: 8px;
  background: var(--vp-c-bg-soft);
  color: var(--vp-c-text-1);
  font-weight: 600;
  line-height: 1.35;
  text-decoration: none;
}

.ja-report-link-card:hover {
  border-color: var(--vp-c-brand-1);
  color: var(--vp-c-brand-1);
}

.partner-logo-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(180px, 1fr));
  gap: 20px;
  width: min(1040px, 100%);
  margin: 0 auto 32px;
  padding: 0 24px;
}

.partner-logo-card {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 112px;
  padding: 18px 24px;
  border: 1px solid rgba(148, 163, 184, 0.22);
  border-radius: 16px;
  background: rgba(255, 255, 255, 0.94);
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.08);
}

.partner-logo-card img {
  display: block;
  width: auto;
  max-width: 190px;
  max-height: 60px;
  object-fit: contain;
}

.partner-logo-card-square img {
  max-width: 76px;
  max-height: 76px;
}

.partner-logo-card-wide img {
  max-width: 210px;
  max-height: 54px;
}

.partner-media-grid {
  grid-template-columns: repeat(2, minmax(220px, 320px));
  justify-content: center;
  width: min(720px, 100%);
}

.partner-logo-card-media {
  min-height: 96px;
}

.partner-logo-card-media img {
  width: 230px;
  height: 64px;
  max-width: 100%;
  object-fit: cover;
}

.dark .partner-logo-card {
  background: rgba(255, 255, 255, 0.96);
  border-color: rgba(255, 255, 255, 0.16);
}

@media (max-width: 768px) {
  .ja-report-link-grid,
  .partner-logo-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 14px;
    padding: 0 16px;
  }

  .partner-logo-card {
    min-height: 96px;
    padding: 16px;
  }
}

@media (max-width: 480px) {
  .ja-report-link-grid,
  .partner-logo-grid,
  .partner-media-grid {
    grid-template-columns: 1fr;
  }
}
</style>
