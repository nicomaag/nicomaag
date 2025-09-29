<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:42b883,100:34d058&height=190&section=header&text=Vue%20Enthusiast&fontSize=70&animation=fadeIn&fontColor=ffffff&fontAlign=60)

# `<Nico.code />` 
### Turning Coffee into Automation since 1997 ☕️

[![Portfolio](https://img.shields.io/badge/Portfolio-nicoma.ag-42b883?style=for-the-badge&logo=vue.js&logoColor=white)](https://nicoma.ag)
[![GitHub](https://img.shields.io/badge/Follow-nicomaag-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nicomaag)

<img src="https://media.giphy.com/media/RbDKaczqWovIugyJmW/giphy.gif" width="400"/>

</div>

## 🚀 Vue Component Showcase

```vue
<!-- Developer.vue -->
<template>
  <div class="developer-card">
    <ProfileHeader
      :name="profile.name"
      :title="profile.title"
      :years-of-experience="10+"
    />
    <SkillMatrix :skills="profile.skills" />
    <CurrentProject
      v-for="project in activeProjects"
      :key="project.id"
      :name="project.name"
      :stack="project.stack"
      @deploy="handleDeploy"
    />
  </div>
</template>

<script setup>
const profile = {
  name: 'Nico',
  title: 'Automation Wizard',
  skills: ['Vue.js', 'C#', 'JavaScript', 'HTML', 'CSS'],
  motto: 'If it can be automated, it will be automated'
}

const activeProjects = [
  { id: 1, name: 'OutfitPicker', stack: ['Vue.js', 'Node.js'] },
  { id: 2, name: 'nicoma-therapy', stack: ['JavaScript', 'Vue.js'] },
  { id: 3, name: 'rexx', stack: ['Node.js', 'Puppeteer'] }
]

const handleDeploy = (projectId) => {
  console.log('🚀 Deploying project:', projectId)
}
</script>

<style scoped>
.developer-card {
  border-radius: 8px;
  background: linear-gradient(135deg, #42b883 0%, #34d058 100%);
}
</style>
```

## 🎯 Projects in Production

<div align="center">

| Project | Status | Tech Stack |
|---------|--------|------------|
| [🎨 OutfitPicker](https://github.com/nicomaag/OutfitPicker) | `yarn dev` | `Vue.js` `Node.js` |
| [🤖 rexx](https://github.com/nicomaag/rexx) | `docker run` | `Node.js` `Docker` |
| [📦 nicoma-node](https://github.com/nicomaag/nicoma-node) | `private` | `Node.js` |
| [🍎 nicoma-macos](https://github.com/nicomaag/nicoma-macos) | `private` | `macOS` |

</div>

## 💻 Tech Stack

```vue
<template>
  <TechStack>
    <StackCategory name="Frontend">
      <Skill name="Vue.js" level="Expert" icon="🚀" />
      <Skill name="JavaScript" level="Expert" icon="💫" />
      <Skill name="HTML/CSS" level="Advanced" icon="🎨" />
    </StackCategory>
    
    <StackCategory name="Backend">
      <Skill name="C#" level="Expert" icon="⚡️" />
      <Skill name="Node.js" level="Advanced" icon="🛠" />
    </StackCategory>
    
    <StackCategory name="DevOps">
      <Skill name="Docker" level="Advanced" icon="🐳" />
      <Skill name="Automation" level="Wizard" icon="🤖" />
    </StackCategory>
  </TechStack>
</template>
```

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nicomaag&show_icons=true&theme=vue&hide_border=true" width="49%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nicomaag&theme=vue&hide_border=true" width="49%" />
</div>

## 🎵 Current Status

<div align="center">

| When I'm... | I'm Probably... |
|-------------|----------------|
| 🎨 Coding | Building in Vue.js |
| 🤖 Automating | Making life easier |
| 📚 Learning | Exploring new tech |
| 🎮 Gaming | When tests pass ✅ |

</div>

---

## <🎲 Fun Facts />

<table>
<tr>
<td width="50%">

```javascript
const nico = {
  favoriteEmoji: "🚀",
  dailyMood: "Let's automate it!",
  superPower: "Turning coffee into code",
  hobbies: [
    "Creating helpful tools",
    "Learning new tech",
    "Solving puzzles"
  ]
}
```

</td>
<td width="50%">
<img src="https://media.giphy.com/media/CuuSHzuc0O166MRfjt/giphy.gif" width="100%">
</td>
</tr>
</table>

<div align="center">

### `return "Thanks for visiting! 👋"`

<img src="https://komarev.com/ghpvc/?username=nicomaag&color=42b883" alt="Profile views" />

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:34d058,100:42b883&height=120&section=footer)

</div>
