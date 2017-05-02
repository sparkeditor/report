# Spark Collaborative Editor Final Report
by Jeremy Dormitzer

## Abstract
For my senior project, I decided to build a collaborative text editor in the style of Google Docs. I hoped to make a tool that could support remote pair programming, in the classroom and in the workplace. After drafting an ambitious plan, I pared down the scope of the project to a more realistic level. The final result was a basic web-based text editor with some advanced features and full support for collaborative editing of documents. Although the software I built was not as fully-featured as I had hoped, I considerably advanced my software engineering skills and built a basic product that could be built upon in the future.

## Introduction
For my senior project, I built a web-based collaborative text editor called Spark. My decision to build a pair programming tool was motivated by my experience collaborating with other students on school projects. Although version control tools like `git` or `mercurial` enable collaboration on the project level, they do not offer the ability to collaborate in real time on a single file. Existing tools for real-time collaboration do exist (see the [Background section](#background) for more details); however, these tools have various problems that make them unsuitable or difficult to use. Another major motivation for building Spark was my interest in the open source software movement. I wanted to build a tool that could be developed collectively by an open source community. This influenced my choice of technology - by choosing an all-JavaScript stack, I hoped that more developers would be able to contribute to the project. Unfortunately, I did not end up having time to properly pursue community outreach or repository maintenance (writing a contributing guide, good internal documentation, etc.), so I had to abandon that aspect of the project.

## Background
Collaborative real-time editing on the web is not a new idea. In 2005, a company called Upstartle released Writely, an online word processor that supported real-time collaboration. Writely caused a media buzz, and was later acquired by Google and rebranded as Google Docs, a collaborative rich text editor that remains at the top of the web-based word processing market. However, Google Docs does not have any code editing features, such as syntax highlighting, autocompletion, or error checking. More recently, some companies have built complete web-based IDEs (integrated development environments). These projects include syntax highlighting and other code editing features. Some even give users web access to a VPS (virtual private server) in which they can compile, test, and run their code. These editors include [Squad](https://squadedit.com), [Firepad](https://firepad.io), and [Cloud9](https://c9.io), among others. When I initially researched this topic, I thought that all existing solutions were proprietary, i.e. closed source, but further research revealed that Firepad is in fact open source. As it turns out, Firepad is pretty similar to the project that I wanted to build, although it was meant to be embedded rather than running as a standalone application.

The application that I wanted to build would have stood out from existing projects (perhaps other than Firepad) due to its open-source community and its focus on pair programming. However, because I did not achieve everything I had outlined, Spark is instead in a position where it can draw influence and inspiration from other web-based text editors.

## Methods

## Results

### Lessons Learned

## Conclusions
