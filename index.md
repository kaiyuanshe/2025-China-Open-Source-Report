---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "2025 中国开源年度报告"
  text: ""
  tagline: 开源社联合多家单位，纵横近十年对中国开源行业的综合性报告，每年发布一次
  actions:
    - theme: brand
      text: 立即阅读 2025 年度报告
      link: /preface
    - theme: alt
      text: 往年报告
      link: https://kaiyuanshe.feishu.cn/wiki/wikcnUDeVll6PNzw900yPV71Sxd

features:
  - icon:
      src: "/image/home/KaiYuanShe-logo.png"
      width: 40
      height: 40
    title: 开源社
    details: 开源社（英文名称为“KAIYUANSHE”）成立于 2014 年，是由志愿贡献于开源事业的个人志愿者，依 “贡献、共识、共治” 原则所组成的开源社区。开源社始终维持 “厂商中立、公益、非营利” 的理念，以 “立足中国、贡献全球，推动开源成为新时代的生活方式” 为愿景，以 “开源治理、国际接轨、社区发展、项目孵化” 为使命，旨在共创健康可持续发展的开源生态体系。
    link: https://kaiyuanshe.cn/
    linkText: 官网
  - icon:
      src: "/image/home/x_lab2017_logo.jpg"
      width: 40
      height: 40
    title: X-lab 开放实验室
    details: X-lab 开放实验室定位为一个开源研究与创新的开放群体，是一群由来自国内外著名高校、创业公司、部分互联网与IT企业的专家学者与工程师所构成，聚焦于开源软件产业开放式创新的共同体。专业背景包括计算机科学、软件工程、数据科学、工商管理学、社会学、经济学等跨学科领域，长期思考并实践开源战略、开源测量学、开源数字生态系统等主题。目前已在包括开源治理标准制定、开源社区行为度量与分析、开源社区流程自动化、开源全域数据治理与洞察等方面做出了较有影响力的工作。
    link: https://github.com/X-lab2017
    linkText: GitHub 链接
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

// 卷首语
const forewordMembers = [
  {
    avatar: withBase('/image/home/avatar/江波.jpg'),
    name: '江波',
  }
]

// 问卷篇
const questionnaireDesignMembers = [
  {
    avatar: withBase('/image/home/avatar/谢思怡.jpg'),
    name: '谢思怡',
  },
];

// 数据篇
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

// 商业化篇
const commercializationMembers = [
  {
    avatar: withBase('/image/home/avatar/袁滚滚.jpg'),
    name: '袁滚滚',
  },
];

// 开源人工智能篇
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
    title: '基础建设部分',
  },
  {
    avatar: withBase('/image/home/avatar/tedwang.jpg'),
    name: '刘天栋',
  },
];

// 开源具身智能篇
const eiMembers = [
  {
    avatar: withBase('/image/home/avatar/江波.jpg'),
    name: '江波',
  },
  {
    avatar: withBase('/image/home/avatar/陈阳.jpg'),
    name: '陈阳',
  },
];


// Web3.0 篇
const web3Members = [
  {
    avatar: withBase('/image/home/avatar/ian-xu.png'),
    name: '许银 Ian Xu',
    title: 'Web3.0 基础分析',
  },
  {
    avatar: withBase('/image/home/avatar/pseudoyu.jpg'),
    name: 'pseudoyu',
    title: 'Web3insight.ai 数据支持',
  },
];

// 大事记篇
const memorabiliaMembers = [
  {
    avatar: withBase('/image/home/avatar/庄表伟.jpg'),
    name: '庄表伟',
    title: "总体章节",
  },
  {
    avatar: withBase('/image/home/avatar/梁尧.jpg'),
    name: '梁尧',
    title: "汽车领域开源",
  },
  {
    avatar: withBase('/image/home/avatar/李明康.jpg'),
    name: '李明康',
    title: "开源教育",
  },
]

// 翻译团队
const translations = [
  {
    avatar: 'https://avatars.githubusercontent.com/u/1667148?v=4',
    name: '高须正和 / TAKASU Masakazu',
    title: '日文版翻译・校阅・维护',
    links: [
      { icon: 'github', link: 'https://github.com/takasumasakazu' },
      { icon: 'link', link: 'https://takasumasakazu.net/' }
    ],
  },
]

// 整体报告汇总/编辑排版
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
];

// 基础设施支持
const infrastructureMembers = [
  {
    avatar: withBase('/image/home/avatar/庄表伟.jpg'),
    name: '庄表伟',
  },
]

</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>编写团队</template>
  </VPTeamPageTitle>

  <VPTeamPageSection v-if="convener">
    <template #title>召集人</template>
    <template #members>
      <VPTeamMembers size="small" :members="convener" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="forewordMembers">
    <template #title>卷首语</template>
    <template #members>
      <VPTeamMembers size="small" :members="forewordMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="questionnaireDesignMembers">
    <template #title>问卷篇</template>
    <template #members>
      <VPTeamMembers size="small" :members="questionnaireDesignMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="dataPieceMembers">
    <template #title>数据篇</template>
    <template #members>
      <VPTeamMembers size="small" :members="dataPieceMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="commercializationMembers">
    <template #title>商业化篇</template>
    <template #members>
      <VPTeamMembers size="small" :members="commercializationMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="aiMembers">
    <template #title>开源人工智能篇</template>
    <template #members>
      <VPTeamMembers size="small" :members="aiMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="eiMembers">
    <template #title>开源具身智能篇</template>
    <template #members>
      <VPTeamMembers size="small" :members="eiMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="web3Members">
    <template #title>Web3.0 篇</template>
    <template #members>
      <VPTeamMembers size="small" :members="web3Members" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="memorabiliaMembers">
    <template #title>开源大事记</template>
    <template #members>
      <VPTeamMembers size="small" :members="memorabiliaMembers" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="translations">
    <template #title>翻译团队</template>
    <template #members>
      <VPTeamMembers size="small" :members="translations" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="copyreaders">
    <template #title>整体报告汇总/编辑</template>
    <template #members>
      <VPTeamMembers size="small" :members="copyreaders" />
    </template>
  </VPTeamPageSection>

  <VPTeamPageSection v-if="infrastructureMembers">
    <template #title>基础设施支持</template>
    <template #members>
      <VPTeamMembers size="small" :members="infrastructureMembers" />
    </template>
  </VPTeamPageSection>

  <!-- <VPTeamPageSection v-if="artWorkers">
    <template #title>设计/排版</template>
    <template #members>
      <VPTeamMembers size="small" :members="artWorkers" />
    </template>
  </VPTeamPageSection> -->
</VPTeamPage>

<!-- <VPTeamPageTitle>
  <template #title>点评专家</template>
  <template #lead>
    （按姓氏字母顺序列名）
  </template>
</VPTeamPageTitle>

<p :style="{fontSize: '1.5rem', textAlign: 'center'}">郭雪、姜宁、蒋涛、tison、卫剑钒、余杰</p> -->

<VPTeamPageTitle>
  <template #title>协作开源社区/单位</template>
</VPTeamPageTitle>

<div class="partner-logo-grid">
  <span class="partner-logo-card partner-logo-card-square">
    <img src="/image/home/KaiYuanShe-logo.png" alt="开源社"/>
  </span>
  <span class="partner-logo-card partner-logo-card-square">
    <img src="/image/home/x_lab2017_logo.jpg" alt="X-lab 开放实验室"/>
  </span>
  <span class="partner-logo-card partner-logo-card-wide">
    <img src="/image/home/logo-dark-FIT2CLOUD.svg" alt="FIT2CLOUD 飞致云"/>
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
  <template #title>合作媒体</template>
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
  .partner-logo-grid,
  .partner-media-grid {
    grid-template-columns: 1fr;
  }
}
</style>
