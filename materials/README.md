## General slide styles

Title slides:

```yaml
format:
  revealjs:
    title-slide-attributes: 
      data-background-image: ../../img/background-hex-shapes.svg
      data-background-opacity: "0.5"
      data-background-gradient: "linear-gradient(30deg, {{< brand color yellow >}}, {{< brand color red >}})"
```

Section slides:

```markdown
# Section title {background-color='{{< brand color yellow >}}' background-image='../../img/background-hex-shapes.svg' background-opacity='0.5'}
```

Your turn slides:

```markdown
# Your turn {background-color='{{< brand color cyan >}}' background-image='../../img/background-hex-shapes.svg' background-opacity='0.5'}
```
