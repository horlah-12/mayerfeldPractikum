Assignment (Main CSS Project):

So for this one, you will have to create a responsive website that is 3-5 pages long (including the landing page). 

As your client, I have provided you with some
instructions and I want you to create my website for me. I don’t know what content I want you
to use, I am a client and I do not need to know that hahaha, so use what you seem fit. some

a) Download the ‘Roboto’ font from here

b) Check out here on how to use that font you just downloaded

c) Have a look at the two images below (3rd/4th) page of this document). One is the design
that you will try to copy, it should look as similar as possible. The second one shows
some information like colors and font-weights you should use in texts.

d) For the section you’re working on, begin by getting all the content onto the page before
beginning to style it. In other words, do the HTML and then do the CSS. You’ll probably
have to go back to the HTML once you start styling, but bouncing back and forth from
the beginning will take more time and may cause more frustration.

e) There are many ways to tackle a project like this, and it can be overwhelming to look at a
blank HTML document and not know where to start. Our suggestion: take it one section
at a time. The website you’re creating has 4 main sections (and a footer), so pick one and
get it into pretty good shape before moving on. Starting at the top is always a solid plan.

f) You will need to work on this as a team, so make a collaborative repository on GitHub
and participate

g) You are not allowed to use any libraries, frameworks or SASS! Use only vanilla HTML
and CSS



------




# 🧑 💻 Workflow on GitHub

This project uses a workflow based on **branches** to ensure orderly, collaborative and change-controlled development.  
The goal is to keep the main branch always stable and facilitate the revision of the code.

---

## 🌿 Main branch (`main`)

- The `main` branch contains **the stable version of the project**.
- All development takes place **out of `main`**.
- Only code is merged in `main` using **Pull Requests**.

---

## 🔄 1. Update the main branch

Before starting any development, it is mandatory to ensure that you have the most up-to-date version of the project.

```bash
git checkout main
git pull origin main
````

This avoids conflicts and ensures that you work on the latest version of the code.

---

## 🌱 2. Create a branch for every development

For each relevant functionality, user story, or task, a **specific branch** should be created from `main`.

```bash
git checkout -b feature/name-descriptiv
````

Examples of branch names:
- `feature/page_name`
- `feature/*******`
- `feature/details`
- `fix/bug-login`

---

## 📝 3. Make small and frequent commits

During development:
- Small and frequent **commits must be performed**.
- Each commit must represent a concrete advance (a task, adjustment or improvement).

Good practices:
- ❌ Do not make a single commit at the end of the development.
- ✅ Make commits when completing functional parts.

```bash
git add .
git commit -m "descriptive message of change"
````

This facilitates code review and progress tracking.

---

## 🔁 4. Keep the development branch updated

If development is prolonged over time, it is advisable to periodically bring the changes of `main` to avoid large conflicts.

```bash
git pull origin main
git checkout feature/name-descriptive
git merge main
````
---

## 🔀 5. Create Pull Request

When the task or functionality is **completely finished and tested**:

1. Up the branch to the remote repository.
2. Create a **Pull Request** from GitHub:
   - Origin: development branch
   - Destination: `main`
   - Add a clear description of the changes made.
     
```bash
git push origin feature/name-descriptive
````

---

## ✅ 6. Review and merge

- The Pull Request must be reviewed before merging.
- If everything is right:
  - The **merge is done in `main`**.
  - The development branch can be removed.

The `main` branch should always be in a stable and functional state.

---

## 📌 Workflow Summary

1. Update the `main` branch
2. Create a branch for development
3. Make small and frequent commits
4. Keep the branch updated with `main` if necessary
5. Create a Pull Request at the end
6. Review and merge in `main`

---

## 🎯 Flow target

This workflow allows:
Avoid unnecessary conflict
- Facilitate teamwork
- Keep a history of change clear
- Ensure a stable main branch

