---
order: 1
title: 
  zh-CN: 位置
  en-US: Placement
---

## zh-CN

位置有 12 个方向。

## en-US 

The ToolTip has 12 placements choice.

````jsx
import { Tooltip } from 'antFB';
const text = <span>prompt text</span>;

ReactDOM.render(
  <div>
    <div style={{ marginLeft: 60 }}>
      <Tooltip placement="topLeft" title={text}>
        <a href="#">topLeft</a>
      </Tooltip>
      <Tooltip placement="top" title={text}>
        <a href="#">top</a>
      </Tooltip>
      <Tooltip placement="topRight" title={text}>
        <a href="#">topRight</a>
      </Tooltip>
    </div>
    <div style={{ width: 60, float: 'left' }}>
      <Tooltip placement="leftTop" title={text}>
        <a href="#">leftTop</a>
      </Tooltip>
      <Tooltip placement="left" title={text}>
        <a href="#">left</a>
      </Tooltip>
      <Tooltip placement="leftBottom" title={text}>
        <a href="#">leftBottom</a>
      </Tooltip>
    </div>
    <div style={{ width: 60, marginLeft: 270 }}>
      <Tooltip placement="rightTop" title={text}>
        <a href="#">rightTop</a>
      </Tooltip>
      <Tooltip placement="right" title={text}>
        <a href="#">right</a>
      </Tooltip>
      <Tooltip placement="rightBottom" title={text}>
        <a href="#">rightBottom</a>
      </Tooltip>
    </div>
    <div style={{ marginLeft: 60, clear: 'both' }}>
      <Tooltip placement="bottomLeft" title={text}>
        <a href="#">bottomLeft</a>
      </Tooltip>
      <Tooltip placement="bottom" title={text}>
        <a href="#">bottom</a>
      </Tooltip>
      <Tooltip placement="bottomRight" title={text}>
        <a href="#">bottomRight</a>
      </Tooltip>
    </div>
  </div>
, mountNode);
````

<style>
#components-tooltip-demo-placement a {
  display: inline-block;
  line-height: 32px;
  height: 32px;
  width: 60px;
  font-size: 14px;
  text-align: center;
  background: #f5f5f5;
  margin-right: 1em;
  margin-bottom: 1em;
  border-radius: 6px;
}
</style>
