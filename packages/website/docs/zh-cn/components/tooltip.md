# Tooltip / 文字提示

在悬停时显示额外的提示信息 。

<playground title="默认的" desc="基础示例" name="ex-tooltip-default" />

<playground title="触发方式" desc="具有不同的触发方式" name="ex-tooltip-trigger" />

<playground title="变体" desc="具有不同的状态" name="ex-tooltip-variable" />

### Tooltip Props

| 属性                | 描述                       | 类型      | 可选值                                                                                                                               | 默认         |
| ------------------- | -------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------ |
| **v-model:visible** | 控制提示框的显示与隐藏     | `boolean` | `true,false`                                                                                                                         | `false`      |
| **type**            | 不同的文字提示类型         | `string`  | `'default', 'success', 'warning', 'error'`                                                                                           | `default`    |
| **content**         | 提示的文字内容             | `string`  | `-`                                                                                                                                  | `true,false` |
| **placement**       | 提示框与目标的对齐方式     | `string`  | `'top', 'topStart', 'topEnd', 'left', 'leftStart', 'leftEnd','bottom', 'bottomStart','bottomEnd', 'right', 'rightStart', 'rightEnd'` | `top`        |
| **visible-arrow**   | 显示箭头                   | `boolean` | `true,false`                                                                                                                         | `true`       |
| **show-after**      | 延迟显示                   | `number`  | `-`                                                                                                                                  | `0`          |
| **hide-after**      | 延迟消失                   | `number`  | `-`                                                                                                                                  | `0`          |
| **offset**          | 提示框与目标之间的偏移(px) | `number`  | `-`                                                                                                                                  | `12`         |
| **portal-class**    | 弹出框类名                 | `string`  | `-`                                                                                                                                  | `-`          |

### Tooltip customSlots

<fe-card>
  Tooltip组件默认提供了<fe-code>content</fe-code>插槽。启用时<fe-code>props.content</fe-code>
  便会失效。
</fe-card>
