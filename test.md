---
title: "Breaking Down Geocoding in R: A Complete Guide"
subtitle: "How to use APIs to find a place you are interested in and visualize it on a map"
author: "Oleksandr Titorchuk"
date: "25.04.2020"
output: html_document
# output:
#   md_document:
#     variant: markdown_github
# output:
#     bookdown::pdf_document2:
#     number_sections: TRUE
# always_allow_html: yes
urlcolor: blue
---

## Introduction

If you ever wondered how to build maps similar to the ones you constantly see in your apps, it's probably a good place to start. In this tutorial we will cover how to find a place based on its description or coordinates and how to build a simple map based on that information.

Please note that this article assumes some prior knowledge of R language: data structures, operators, conditional statements, functions etc. All the code from this tutorial can be found on [GitHub](https://github.com/s-titoo/Geocoding-in-R).

So, let's get started!