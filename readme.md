# Curriculum Vitae template

This repository serves as a template project designed to simplify the process of hosting your Curriculum Vitae (CV) on GitHub Pages. With this template, you can effortlessly showcase your professional profile and accomplishments to potential clients, collaborators, or anyone interested in learning more about you.

By leveraging GitHub Pages, a feature that allows you to host static websites directly from your GitHub repositories, you can create a professional-looking online CV without the need for complex web hosting setups or services. GitHub Pages automatically builds and serves your CV website from the files in this repository, making it accessible to anyone with an internet connection.

With the structure and configuration provided in this template, you can easily customize your CV content, layout, and styling to reflect your unique skills, experiences, and personality. Whether you're a seasoned professional looking to highlight your career achievements or a recent graduate showcasing your academic accomplishments, this template offers a flexible and user-friendly solution for creating and maintaining your online CV.

Get started today by forking this repository and following the setup instructions in the README.md file. Elevate your online presence and make your CV easily accessible to the world with this GitHub Pages template.

## Table of Contents

- [Forking to your own github](#Forking-to-your-own-github)
- [Usage](#usage)
- [Editing your CV](#editing-your-cv)
- [Credits](#credits)

## Forking to your own GitHub

To fork this template repository and set up your own CV on GitHub Pages, follow these steps:

1. Navigate to the "code" section of the repository.
2. Click on the "Use this template" button.
3. Create a new repository in your GitHub account. Remember to make it public.
4. Name your repository as desired and click "Create repository".

You will now have your own copy of the CV template in your GitHub account. Next, follow these additional steps:

1. Go to your repository's settings.
2. Navigate to the "Pages" section.
3. In the "Build and deployment" section, choose the source as "GitHub Actions".
4. Save your changes.

Your CV website will now be automatically built and hosted on GitHub Pages. You can customize the content, layout, and styling of your CV by modifying the files in your repository. Share your professional profile with the world effortlessly using this GitHub Pages template.

To access your CV, you can click in the "deployments" subsection on the right part of the code tab.

## Editing your CV

To edit your CV content:

1. Navigate to the "\_data" folder in your repository.
2. Open the data.yml file to edit your template information.
3. Replace the profile picture with your own image (100x100) located in /assets/images/.

## Field Explanation

### Sidebar
- position: Position of the sidebar (left or right)
- about: True/False; set to False or comment out if you want to remove the "how to use?" section in the sidebar
- education: True/False; set to False if you want education in the main section instead of the sidebar
- download: True/False; Set to True if you want to enable PDF download

### Profile Information
- name: Consultant Name
- tagline: Consultant Title
- avatar: Place a 100x100 picture inside the /assets/images/ folder and provide the filename below
- email: Self-explanatory
- timezone: City where the timezone is located
- nationality: Self-explanatory
- github: GitHub URL

### Languages Section
- title: Section title
- info: Section containing language and level
- idiom: Language
- level: Highest level of the language

### Interests Section
- title: Section title
- info: Container for the section object
- item: Interest name
- link: Any URL to share related information

### Career Section
- This section goes at the top of the profile.
- title: Your career title
- summary: A brief description of your career

### Experiences Section
- This section contains all the projects you have been working on.
- title: Container name
- info: Container to fill the position data
- role: Role name
- time: Time frame for the working period
- company: Company name
- details: Extended description for the position itself

### Education Section
- title: Section title
- info: Container for the section data
- degree: Degree name
- university: Name of university
- time: From/to duration of the degree
- details: Description details of the degree

### Projects Section
- title: Section title
- intro: Description of the project
- assignments: Section for project details
- title: Project title
- link: Any URL for the project
- tagline: Brief description

### Certifications Section
- title: Section title
- list: Container for the section data
- name: Certification name
- start: Start year
- end: End year
- organization: Certifier organization
- credentialid: Certification number
- credentialurl: URL related if any
- credential name: Credential name if any
- details: Certification description

### Skills
- Tools and skills section
- title: Section title
- categories: Container for the section data
- title: Skill container title
- toolset: Section for the skill container
- name: Skill/tool name
- years: Mandatory number
- level: Non-mandatory percentage (x%) to draw the percentage bars

## Credits

Theme:
[Sharath Kumar](https://github.com/sharu725/online-cv)

Development:
[Umut Ay Bora](https://github.com/Umutayb)
[Facundo Paolini](https://github.com/FisSher)
