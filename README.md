# Developer Portfolio

### Are you struggling to create a professional portfolio website? Look no further! You can use the Developer Portfolio template and create your very own personalized portfolio today! My website is designed to be user-friendly and easily customizable, making it perfect for both developers and freelancers.

---
<br/>
# Demo :movie_camera:

![](./public/image/screen.png)
<br/>
## View live preview [here](https://darshandesai.netlify.app/).

---
<br/>
## Table of Contents :scroll:

- [Sections](#sections-bookmark)
- [Demo](#demo-movie_camera)
- [Installation](#installation-arrow_down)
- [Getting Started](#getting-started-dart)
- [Usage](#usage-joystick)
- [Packages Used](#packages-used-package)
<br/>
---

# Sections :bookmark:

- HERO SECTION
- ABOUT ME
- EXPERIENCE
- SKILLS
- PROJECTS
- EDUCATION
- BLOG
- CONTACTS
<br/>
---
&nbsp;
# Installation :arrow_down:

### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)
<br/>
&nbsp;
#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```<br/>

## <br />

# Getting Started :dart:

### Fork and Clone the repo

To Fork the repo click on the fork button at the top right of the page. Once the repo is forked open your terminal and perform the following commands

```<br/>
git clone https://github.com/<YOUR GITHUB USERNAME>/developer-portfolio.git

cd developer-portfolio
```
<br/>
&nbsp;
&nbsp;
### Install packages from the root directory

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---
<br/>
# Usage :joystick:

Goto [emailjs.com](https://www.emailjs.com/) and create a new account for the mail sending. In free trial you will get 200 mail per month. After setup `emailjs` account, Please create a new `.env` file from `.env.example` file.

Eg:

```env
NEXT_PUBLIC_EMAILJS_SERVICE_ID =
NEXT_PUBLIC_EMAILJS_TEMPLATE_ID =
NEXT_PUBLIC_EMAILJS_PUBLIC_KEY =
NEXT_PUBLIC_GTM = # For site analytics
NEXT_PUBLIC_APP_URL = "http://127.0.0.1:3000"
NEXT_PUBLIC_RECAPTCHA_SECRET_KEY = # For captcha verification on contact form
NEXT_PUBLIC_RECAPTCHA_SITE_KEY =
```
<br/>
### Then, Customize data in the `utils/data` [folder](https://github.com/said7388/developer-portfolio/tree/main/utils/data).

Eg:

```javascript
export const personalData = {
  name: "your name",
  profile: "/profile.png",
  designation: "Full-Stack Software Developer",
  description: "My name is Name....",
  email: "emailgmail.com",
  phone: "+91 0000000XXX",
  address: "your address ",
  github: "https://github.com/username",
  facebook: "https://www.facebook.com/username/",
  linkedIn: "https://www.linkedin.com/in/username/",
  twitter: "https://twitter.com/username",
  stackOverflow: "https://stackoverflow.com/username",
  leetcode: "https://leetcode.com/username/",
  devUsername: "username",
  resume: "your google drive link",
};
```

`devUsername` Used for fetching blog from `dev.to`.

---

---
<br/>
# Packages Used :package:

| Used Package List  |
| :----------------: |
|        next        |
|  @emailjs/browser  |
|    lottie-react    |
| react-fast-marquee |
|    react-icons     |
|   react-toastify   |
|        sass        |
|    tailwindcss     |

---
#   p o r t f o l i o 
 
 #   P o r t f o l i o 
 
 #   P o r t f o l i o 
 
 # Portfolio
