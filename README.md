
```java
class ConanDolye{
    public static void main(String[] argc){
        System.out.println("Hello Kitaajya!,I am a doctor named Conan Doyle!");
        Kitaajya.introduct();
    }
}
public class Kitaajya {
    interface Developer {
        String getName();
        String getAlias();
        String[] getTechStack();
        String getCurrentProject();
    }

    public static void introduct() {
        Developer me = new Developer() {
            public String getName() { return "柯南·道尔"; }
            public String getAlias() { return "Kitaajya"; }
            public String[] getTechStack() { return new String[]{"Java 17", "Spring Boot", "Spring AI", "MySQL"}; }
            public String getCurrentProject() { return "YouTube_Imitate（深度接入 AI）"; }
        };

        System.out.println("=====================================");
        System.out.printf("你好！我是 %s（又名 %s）%n", me.getName(), me.getAlias());
        System.out.printf("正在做: %s%n", me.getCurrentProject());
        System.out.printf("技术栈: %s%n", String.join(" | ", me.getTechStack()));
        System.out.println("目标: 重构操作系统。");
        System.out.println("=====================================");
    }
}
```

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kitaajya&theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kitaajya&theme=default">
    <img width="100%" alt="Profile Details" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kitaajya&theme=github_dark">
  </picture>
</div>

# Hi there, I'm Conan Doyle, aka Kitaajya 👋

### 嗨！我是柯南·道尔，又名 Kitaajya 👋

**🌐 语言 / Language / 言語：** [中文](#中文) · [English](#english) · [日本語](#日本語) · [⬆ 回到顶部](#hi-there-im-conan-doyle-aka-kitaajya-)

![github contribution grid snake animation](https://raw.githubusercontent.com/Kitaajya/Kitaajya/output/github-snake.svg)

---

<a id="中文"></a>

## 🇨🇳 中文

**来自中国地质大学长城学院的学子 · 目标是重构操作系统**

本名：亚当斯·柯南·道尔　|　外号：忧郁的神医、唐山名医

[![Website](https://img.shields.io/badge/Website-Kitaajya-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kitaajya)
[![Email](https://img.shields.io/badge/Email-conandoyle1@qq.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:conandoyle1@qq.com)

### 🚀 关于我

- 🔭 **正在做**：仿 YouTube 大型全栈视频网站（包含短视频流、私信系统、AI 赋能）
- 🤖 **AI 实践**：深度集成 Spring AI，基于大模型实现数据库智能检索与流式对话
- 📫 **联系我**：conandoyle1@qq.com

### 🌱 技术栈

| 层级 | 技术 |
| :--- | :--- |
| **后端** | Java 17 · Spring Boot · Spring MVC · Spring AI |
| **持久层** | MyBatis（注解/动态 SQL）· MySQL 8（InnoDB / 复杂窗口函数） |
| **前端** | 原生 HTML / CSS / JavaScript（无框架、无构建、Fetch API） |
| **中间件** | Caffeine 本地缓存 · Multipart 大文件流式存储 |
| **鉴权** | HttpSession · 图形验证码（AWT） |

### 📊 GitHub 统计

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Kitaajya&show_icons=true&theme=dark&hide_border=true&locale=cn)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Kitaajya&layout=compact&theme=dark&hide_border=true&locale=cn)

</div>

### 🛠️ 常用工具与技术

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo=mybatis&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

### 📌 精选项目

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>▶️ <a href="https://github.com/Kitaajya/Youtube_Imitate">Youtube_Imitate</a></h3>
      <p>使用 Spring Boot + 原生 JS 深度模拟的 YouTube。包含了视频瀑布流、短视频划动、历史记录、复杂的评论盖楼与点赞、消息红点通知，以及自研的私信系统（支持富媒体、消息撤回与软删除）。</p>
      <p><b>✨ 核心亮点：</b>接入 Spring AI 与 DeepSeek，支持 AI 流式问答，并可通过自然语言直接分析数据库内的用户与点赞数据。</p>
    </td>
    <td width="50%" valign="top">
      <h3>🎬 <a href="https://github.com/Kitaajya/Bilibili_1st">Bilibili_1st</a></h3>
      <p>模拟 Bilibili 的项目，主要用于练习前后端分离架构、RESTful API 设计、文件上传下载以及视频站点的业务逻辑。</p>
    </td>
  </tr>
</table>

---

<a id="english"></a>

## 🇬🇧 English

**Student at China University of Geosciences Great Wall College · On a mission to rebuild an operating system**

Real name: Adams Conan Doyle　|　Nicknames: The Melancholic Physician, The Tangshan Doctor

[![Website](https://img.shields.io/badge/Website-Kitaajya-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kitaajya)
[![Email](https://img.shields.io/badge/Email-conandoyle1@qq.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:conandoyle1@qq.com)

### 🚀 About Me

- 🔭 **Currently working on**: A large-scale YouTube simulation (Shorts, Direct Messaging, AI Integration)
- 🤖 **AI Practice**: Integrating Spring AI for database intelligent retrieval and streaming chat.
- 📫 **Contact me**: conandoyle1@qq.com

### 🌱 Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend** | Java 17 · Spring Boot · Spring MVC · Spring AI |
| **Persistence** | MyBatis (Annotation/Dynamic SQL) · MySQL 8 (InnoDB / Window Functions) |
| **Frontend** | Vanilla HTML / CSS / JavaScript (Fetch API, no frameworks) |
| **Other** | Caffeine Cache · Multipart File Storage |

### 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Kitaajya&show_icons=true&theme=dark&hide_border=true&locale=en)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Kitaajya&layout=compact&theme=dark&hide_border=true&locale=en)

</div>

### 📌 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>▶️ <a href="https://github.com/Kitaajya/Youtube_Imitate">Youtube_Imitate</a></h3>
      <p>A full-stack YouTube clone built with Spring Boot and Vanilla JS. Features include video feeds, Shorts, watch history, nested comments, notification dots, and a custom messaging system (media support, withdrawal, soft delete).</p>
      <p><b>✨ Highlight:</b> Deeply integrated with Spring AI & DeepSeek for streaming chat and natural language database querying.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🎬 <a href="https://github.com/Kitaajya/Bilibili_1st">Bilibili_1st</a></h3>
      <p>A Bilibili-inspired project, practicing full-stack integration, RESTful API design, file I/O, and video-site business logic.</p>
    </td>
  </tr>
</table>

---

<a id="日本語"></a>

## 日本語

**中国地質大学長城学院の学生 · オペレーティングシステムの再構築を目指しています**

本名：アダムス・コナン・ドイル　|　愛称：憂鬱な神医、唐山の名医

[![Website](https://img.shields.io/badge/Website-Kitaajya-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kitaajya)
[![Email](https://img.shields.io/badge/Email-conandoyle1@qq.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:conandoyle1@qq.com)

### 🚀 自己紹介

- 🔭 **現在取り組んでいること**：YouTube を模した大規模フルスタック動画サイト（ショート動画、DM、AI 連携）
- 🤖 **AI 実践**：Spring AI を導入し、データベースのスマート検索とストリーミング対話を実現
- 📫 **連絡先**：conandoyle1@qq.com

### 🌱 技術スタック

| レイヤー | 技術 |
| :--- | :--- |
| **バックエンド** | Java 17 · Spring Boot · Spring MVC · Spring AI |
| **永続層** | MyBatis（アノテーション SQL）· MySQL 8（InnoDB / ウィンドウ関数） |
| **フロントエンド** | 素の HTML / CSS / JavaScript（フレームワークなし、Fetch API） |
| **その他** | Caffeine キャッシュ · Multipart ファイルストレージ |

### 📌 注目プロジェクト

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>▶️ <a href="https://github.com/Kitaajya/Youtube_Imitate">Youtube_Imitate</a></h3>
      <p>Spring Boot と素の JS で構築した YouTube クローン。動画フィード、ショート、履歴、ネストされたコメント、通知、カスタム DM システムを備えています。</p>
      <p><b>✨ ハイライト：</b>Spring AI と DeepSeek を統合し、ストリーミングチャットと自然言語による DB 検索を実現。</p>
    </td>
    <td width="50%" valign="top">
      <h3>🎬 <a href="https://github.com/Kitaajya/Bilibili_1st">Bilibili_1st</a></h3>
      <p>Bilibili を模したプロジェクト。フロントエンドとバックエンドの統合、RESTful API 設計、ファイル I/O を練習しています。</p>
    </td>
  </tr>
</table>

---

⭐️ From [Kitaajya](https://github.com/Kitaajya) · [⬆ Back to Top](#hi-there-im-conan-doyle-aka-kitaajya-)
