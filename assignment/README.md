# GLSLSchhol2018 課題

Slackが新しいロゴに変わったのが印象的だったので、そのアニメーションを真似してみました

[DEMO (glslsandbox)](http://glslsandbox.com/e#52059.0)

（コードがとても汚いので後々修正します…）

## Point
- `linearstep(float begin, float end, float t)` 関数を作り、時間軸に沿ったアニメーションを制作
- 各アニメーションを90度ずつずらして計4つに合成し、それぞれ違う色で塗った

## Reference

- [https://slackhq.com/say-hello-new-logo](https://slackhq.com/say-hello-new-logo)
- [フラグメントシェーダーだけでタイムラインアニメーションを作る考え方](https://qiita.com/null_tokyo/items/bb303228d8ad6fdb613f)
