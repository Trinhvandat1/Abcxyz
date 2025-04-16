<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Trường THPT Lương Tài</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: white;
    }

    header {
      background-color: #D32F2F;
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    .header-top {
      display: flex;
      align-items: center;
      padding: 10px 20px;
      flex-wrap: wrap; /* Cho phép xuống dòng */
    }

    .logo {
      margin-right: 15px;
    }

    .logo img {
      height: 60px;
      width: 60px;
      border-radius: 50%;
    }

    .school-name {
      font-size: 18px;
      font-weight: bold;
      line-height: 1.4;
    }

    nav {
      background-color: #fff;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      border-top: 1px solid #ccc;
      border-bottom: 1px solid #ccc;
    }

    nav a {
      padding: 12px 18px;
      color: #D32F2F;
      text-decoration: none;
      font-weight: bold;
      border-right: 1px solid #ccc;
      white-space: nowrap;
    }

    nav a:last-child {
      border-right: none;
    }

    nav a:hover {
      background-color: #f5f5f5;
    }

    main {
      padding: 40px 20px;
      text-align: center;
    }

    main img {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      margin-bottom: 30px;
    }

    footer {
      background-image: url('https://www.transparenttextures.com/patterns/black-linen.png');
      background-color: #D32F2F;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .school-name {
        font-size: 16px;
        text-align: center;
        width: 100%;
        margin-top: 10px;
      }

      nav a {
        flex: 1 1 50%;
        text-align: center;
        border-right: none;
        border-bottom: 1px solid #ccc;
      }

      nav {
        flex-direction: row;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="header-top">
      <div class="logo">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/Logo_GD%26DT.png/600px-Logo_GD%26DT.png" alt="Logo">
      </div>
      <div class="school-name">
        Sở GD&ĐT Bắc Ninh<br>
        Trường THPT Lương Tài
      </div>
    </div>
    <nav>
      <a href="#">Trang chủ</a>
      <a href="#">Giới thiệu</a>
      <a href="#">Tin tức</a>
      <a href="#">Tuyển sinh</a>
      <a href="#">Liên hệ</a>
    </nav>
  </header>

  <main>
    <img src="https://thptluongtai.bacninh.edu.vn/upload/18291/20200902/thptluongtai.jpg" alt="Ảnh trường">
    <h2>Chào mừng đến với Trường THPT Lương Tài</h2>
    <p>Trường Trung học Phổ thông Lương Tài là một trong những ngôi trường tiêu biểu của tỉnh Bắc Ninh, với bề dày truyền thống dạy tốt - học tốt, đào tạo ra nhiều thế hệ học sinh xuất sắc. Nhà trường luôn chú trọng phát triển toàn diện cho học sinh, từ kiến thức, kỹ năng đến đạo đức.</p>
    <p>Với đội ngũ giáo viên tận tâm và cơ sở vật chất hiện đại, THPT Lương Tài tự hào là mái nhà chung cho hàng ngàn học sinh trên con đường chinh phục tri thức.</p>
  </main>

  <footer>
    <p>© 2025 Trường THPT Lương Tài | Địa chỉ: Huyện Lương Tài, Tỉnh Bắc Ninh</p>
    <p>Email: thptluongtai@example.com | Điện thoại: 0123 456 789</p>
  </footer>

</body>
</html>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Enable GitHub Pages

_Welcome to GitHub Pages and Jekyll :tada:!_

The first step is to enable GitHub Pages on this [repository](https://docs.github.com/en/get-started/quickstart/github-glossary#repository). When you enable GitHub Pages on a repository, GitHub takes the content that's on the main branch and publishes a website based on its contents.

### :keyboard: Activity: Enable GitHub Pages

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. Under your repository name, click **Settings**.
1. Click **Pages** in the **Code and automation** section.
1. Ensure "Deploy from a branch" is selected from the **Source** drop-down menu, and then select `main` from the **Branch** drop-down menu.
1. Click the **Save** button.
1. Wait about _one minute_ then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
   > Turning on GitHub Pages creates a deployment of your repository. GitHub Actions may take up to a minute to respond while waiting for the deployment. Future steps will be about 20 seconds; this step is slower.
   > **Note**: In the **Pages** of **Settings**, the **Visit site** button will appear at the top. Click the button to see your GitHub Pages site.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
