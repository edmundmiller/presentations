```yaml
layout: section
```

# Worktrees

---

```yaml
layout: image-left
image: /you_know_me.png
backgroundSize: contain
```

<v-clicks>

## Have you ever had a lot of active branches going at once?

<br>

## Waiting on GitHub runners to pick up your nf-test job?

<br>

## Can't wait for your PR to merge to get started on the next one?

</v-clicks>

---

```yaml
title: FlexTrees
layout: image
image: https://i.imgflip.com/891vk0.jpg
backgroundSize: contain
```

---

```yaml
layout: image-left
image: /you_know_me.png
backgroundSize: contain
```

<v-clicks>

## Multitasking in Git: A Comedy

Who needs a stand-up routine when you can juggle 27 active branches?

<br>

## CI/CD or Waiting for Water to Boil?

GitHub runners: The only race where you might lose your mind before the finish line.

<br>

## PR Merge Anticipation: A Developer's Cliffhanger

Forget binge-watching your favorite series. The real suspense? The thrill of waiting for that sweet PR merge.

<br>

</v-clicks>

<!-- Asked ChatGPT to make this funnier, did not disappoint -->

---

```yaml
title: Worktrees diagram
layout: image
image: https://www.gitkraken.com/wp-content/uploads/2022/03/Worktrees-01-2048x919.png.webp
backgroundSize: contain
```

<!-- cite: https://www.gitkraken.com/learn/git/git-worktree -->

---

```yaml
title: Worktrees with GitLens+
layout: image
image: https://www.gitkraken.com/wp-content/uploads/2022/03/gl-worktree-add-new-step-1-2048x1280.png.webp
backgroundSize: contain
```

---

```yaml
title: Worktrees with GitLens+
layout: image
image: https://www.gitkraken.com/wp-content/uploads/2022/03/gitlens-worktree-list-e1646441544109.png
backgroundSize: contain
```

---

# For the cli purists

```bash {-4|6|8}
$ git worktree add <PATH>

# Create feature-x directory and branch with the same name.
$ git worktree add ../feature-x

$ git worktree remove feature-x

$ git worktree add -b feature-zzz ../feature-x origin/feature-zzz
```

---

```yaml
title: Git worktree switcher
layout: image
image: https://camo.githubusercontent.com/45b4f483eb593ecafbee452f3c859c43fc6dd83f112f7d5af7a6917328aa833e/68747470733a2f2f692e696d6775722e636f6d2f6e50646e6544542e676966
backgroundSize: contain
```
