prismic-headstart
# Prismic - Headstart

Based on "Slicemachine" at https://prismic.io/docs/technologies/nextjs

See also "Announcing Slice Machine: a workflow for developing and deploying website sections" at "https://prismic.io/blog/announcing-slice-machine"

Slicemachine isn’t the standard component library that you may have seen in the past. It is a tool that will allow you to improve your component workflow. From building the individual components to combining them into actual pages.

***Prismic*** is a **Headless CMS** that offers unlimited custom types, API calls, and a bunch of other great things. You should really check it out.

[Building websites with components | January Prismic Product Meet-up](https://www.youtube.com/watch?v=fiOwHYFkUz0)

The problem is, API-based CMS’s have created a gap between the components and the data that they require and we wanted to bridge that gap.

We took our first step on that journey when we created our Slices feature.

With Slices, you can break your page content into JSON components that correspond to your frontend components. Each Slice represents the JSON model (content) for a given component.

Slices are one of our coolest features and a big reason why so many people are choosing to use Prismic.

But we wanted to find a way to take Slices to the next level and to allow developers to adopt a totally component-based approach to how they build websites and create pages. And that’s why we’ve partnered with Netlify and Nuxt to bring ***Slice Machine*** to life.

# 100 - Introduction

**Slice Machine — Build website sections and combine them into pages***

In it’s most basic form, **Slice Machine** is an open-source CLI and a component library. And just that should be enough to pique your interest.

There are two parts to building pages with components. 

1. The first part is about building and deploying page sections (components). 
2. The second part is about building pages using these components.


## 100 - Building and deploying page sections (components)


## 200 - Building pages using these components

**SliceZone** is a component that you drop into your page and it will take care of calling the necessary components and provide them with their content props to build the page.

This way, all that you have to do is use the visual editor (***Prismic interface***) to define the different Slices - every Slice containing the props that are passed to a given component - and the SliceZone will automatically mirror these Slices by calling the corresponding components in your frontend code.

[Video](https://youtu.be/PO58pGIkDg0)
