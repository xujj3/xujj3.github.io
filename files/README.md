# files/

站点上可公开下载的资料放在这里。文件路径即 URL：`files/<文件名>`。

## 命名约定

```
surname-year-topic.ext

例：
xu-2026-five-step-pipeline.pdf      五步流程培训讲义（脱敏版）
xu-2026-transport-method-note.pdf   输运计算方法说明
```

## 放什么

- ✅ 脱敏后的讲义、方法说明、计算设置模板
- ✅ 可公开的图表、示意图
- ❌ 含企业内部信息、客户数据、集群配置的完整版
- ❌ 单文件超过 50 MB（GitHub 硬限制 100 MB，超过建议用外部存储挂链接）

## 引用方式

在项目条目里写：

```markdown
## 相关材料

- 📄 [五步流程培训讲义（脱敏版）](/files/xu-2026-five-step-pipeline.pdf)
```

或使用 `{{ base.url }}` 前缀保持子路径兼容：

```markdown
- 📄 [讲义]({{ site.baseurl }}/files/xu-2026-five-step-pipeline.pdf)
```
