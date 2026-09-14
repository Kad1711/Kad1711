# Hi, I'm Khả Dương (Kad) 👋

> **Software Engineer** specializing in **Backend Architecture**, **Applied Computer Vision** & **Full-stack Systems**.  
> Focused on building maintainable software, solving real-world domain problems with clean code and practical data pipelines.

[![GitHub](https://img.shields.io/badge/GitHub-Kad1711-181717?style=flat-square&logo=github)](https://github.com/Kad1711)
[![Email](https://img.shields.io/badge/Email-nguyenkhaduong17%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:nguyenkhaduong17@gmail.com)
[![Location](https://img.shields.io/badge/Location-Vietnam-007ACC?style=flat-square)](https://github.com/Kad1711)

---

### 🧠 Core Engineering Focus

- **Applied Computer Vision & OMR:** Document layout analysis, perspective correction (Homography), and optical mark classification.
- **Decoupled Backend Architecture:** Monorepo multi-tier systems, network isolation, RESTful APIs, and relational/document databases.
- **Client & Modern Frontends:** Native Android applications (Kotlin) and responsive SPA frontends (React).

---

### 🛠️ Technical Arsenal

| Layer | Technologies & Tools |
| :--- | :--- |
| **AI & Computer Vision** | Python 3.11, OpenCV, FastAPI, Homography, NumPy, Local LLM (LM Studio) |
| **Backend & Services** | Node.js, Express.js, Prisma ORM, RESTful APIs, JWT, Zod |
| **Databases & Cache** | PostgreSQL 17, MongoDB, SQL Server, Redis |
| **Client Engineering** | Kotlin (Android), React 19, Vite, Tailwind CSS, TypeScript, JavaScript |
| **DevOps & Tooling** | Docker Compose, Pytest, Git/GitHub, Postman, Nginx, Cloudinary |

---

### 🚀 Featured Systems & Projects

#### 1. [Digital Exam Grading V1](https://github.com/Kad1711/DigitalExamGrading)
> **Automated High School OMR Exam Grading System powered by Computer Vision & Decoupled 3-tier Architecture.**
- **Vision Pipeline:** Thuật toán 4 Corner Markers kết hợp Perspective Transform (Homography) nắn phẳng ảnh chụp điện thoại; phân loại ô tô 4 trạng thái (`MARKED`, `BLANK`, `MULTIPLE`, `UNCERTAIN`) và cắt lát ảnh câu hỏi nghi vấn phục vụ phúc khảo.
- **System Architecture:** Kiến trúc Monorepo cô lập ranh giới mạng: React 19 SPA $\leftrightarrow$ Node.js Core API $\leftrightarrow$ Python FastAPI OMR Engine $\leftrightarrow$ PostgreSQL 17.
- **Quality Assurance:** Bộ kiểm thử tự động 37/37 tests PASS (Pytest), chuẩn hóa SBD 6 số chống trùng lặp và bảo vệ dữ liệu học sinh (Data Masking).
- **Stack:** `Python` `OpenCV` `FastAPI` `Node.js` `Prisma` `PostgreSQL 17` `React 19` `Docker Compose`

#### 2. [Spotify Fullstack Clone](https://github.com/spotify-clone-team/Spotify_Fullstack_Clone)
> **End-to-end Audio Streaming Ecosystem: Native Android Client, REST API Server & Admin Dashboard.**
- **Architecture:** Hệ thống phân tách 3 thành phần độc lập: Android client (Mobile), Node.js backend (Core API), và Web admin (Dashboard).
- **Client & Streaming:** Native Android client (Kotlin) xử lý luồng phát audio trực tuyến, đồng bộ playlist và quản lý trạng thái nghe nhạc.
- **Management & Security:** Cổng quản trị web dành cho admin tải lên và kiểm duyệt metadata/audio; xác thực an toàn qua JWT.
- **Stack:** `Kotlin` `Android Studio` `Node.js` `Express` `MongoDB` `React` `REST API`

#### 3. [PhoneStore-AI](https://github.com/Kad1711/PhoneStore-AI)
> **Full-stack E-commerce Platform with Context-Aware Local LLM Sales Assistant.**
- **AI Integration:** Tích hợp mô hình ngôn ngữ lớn cục bộ qua LM Studio API để xử lý ngôn ngữ tự nhiên, phân tích ý định mua sắm và bóc tách thông số kỹ thuật máy.
- **Real-time Engine:** Đối soát dữ liệu cấu hình, màu sắc và trạng thái tồn kho thời gian thực từ MongoDB dựa trên đoạn chat của khách hàng.
- **Security & Data:** Quản trị danh mục sản phẩm, lịch sử hội thoại nhiều lượt và xác thực phiên đăng nhập bằng JWT.
- **Stack:** `Node.js` `Express` `MongoDB` `LM Studio (Local LLM)` `JavaScript` `JWT`

#### 4. [Website_DiSanVanHoa](https://github.com/Kad1711/Website_DiSanVanHoa)
> **Digital Heritage & Literature Education Platform with Interactive Map Integration.**
- **EdTech Platform:** Nền tảng học liệu số chuyên ngành hỗ trợ sinh viên Sư phạm Ngữ văn nghiên cứu học phần Văn học dân gian các dân tộc thiểu số Việt Nam.
- **GIS & Multimedia:** Tích hợp bản đồ số trực quan hóa không gian địa lý văn hóa theo từng tộc người, kết hợp pipeline lưu trữ và phân phối học liệu đa phương tiện (tác phẩm, âm thanh, hình ảnh) qua CDN.
- **Full-stack Workflow:** RESTful API quản lý danh mục tác phẩm và hệ thống phân quyền người dùng tương tác với kho học liệu.
- **Stack:** `React` `Node.js` `Express` `MongoDB` `Cloudinary` `Interactive Map`

---

### 📈 GitHub Analytics

<div align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Kad1711&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=c9d1d9" alt="GitHub Stats" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kad1711&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>"Simplicity is prerequisite for reliability." — Edsger W. Dijkstra</sub>
</div>
