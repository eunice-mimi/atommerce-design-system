# Atommerce Design System — File Structure

서비스별로 문서 파일을 분리한다.
Figma는 하나의 토큰 컬렉션에서 service mode를 사용할 수 있지만, 문서에서는 각 서비스 경로 안에서 해당 서비스 값만 보여준다.

```text
atommerce-design-system/
├── index.html
├── products.html
├── ai-guide.html
├── style.css
├── llms.txt
├── ai-guide/
│   ├── claude-skill.html
│   ├── llms-guide.html
│   └── usage-guide.html
│
├── mindcafe/
│   ├── index.html
│   ├── foundations/
│   │   ├── index.html
│   │   ├── color.html
│   │   ├── typography.html
│   │   ├── grid.html
│   │   ├── radius.html
│   │   ├── elevation.html
│   │   ├── icons.html
│   │   ├── logo.html
│   │   ├── motion.html
│   │   └── accessibility.html
│   ├── components/
│   │   ├── index.html
│   │   ├── button.html
│   │   ├── input.html
│   │   ├── checkbox.html
│   │   └── ...
│   ├── patterns/
│   │   ├── index.html
│   │   └── ...
│   └── templates/
│       ├── index.html
│       └── ...
│
├── tarobom/
│   ├── index.html
│   ├── foundations/
│   │   ├── index.html
│   │   └── color.html
│   ├── components/index.html
│   ├── patterns/index.html
│   └── templates/index.html
│
├── expert/
│   ├── index.html
│   ├── foundations/
│   │   ├── index.html
│   │   └── color.html
│   ├── components/index.html
│   ├── patterns/index.html
│   └── templates/index.html
│
├── center/
│   ├── index.html
│   ├── foundations/
│   │   ├── index.html
│   │   └── color.html   # Coming soon
│   ├── components/index.html
│   ├── patterns/index.html
│   └── templates/index.html
│
└── admin/
    ├── index.html
    ├── foundations/
    │   ├── index.html
    │   └── color.html
    ├── components/index.html
    ├── patterns/index.html
    └── templates/index.html
```

## Color rule
- `mindcafe/foundations/color.html`: MindCafe mode
- `tarobom/foundations/color.html`: Tarobom mode
- `expert/foundations/color.html`: expert mode
- `admin/foundations/color.html`: Admin mode
- `center/foundations/color.html`: 별도 mode 확인 전 Coming soon
