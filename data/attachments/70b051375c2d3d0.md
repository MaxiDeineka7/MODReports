# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - alert ":r17:" [ref=e3]:
    - alert [ref=e4]:
      - heading "Щось пішло не так." [level=1] [ref=e5]
      - link "На Головну" [ref=e6] [cursor=pointer]:
        - /url: /
  - alert [ref=e7]
```