### 组件基于element-ui的el-input输入框封装
### 描述

<p>组件基于element-ui的el-input输入框封装，组件屏蔽了除数字以外的其他输入，支持整数和金额(支持两位小数)两种形式；<p/>
### 例子

```
// 导入
// 组件注册
<number-input type='money' v-model.number="formData.budget" placeholder="请输入数字">
  <i class="el-icon-edit el-input__icon" slot="suffix"></i>
</number-input>
```
### 说明
> type 支持integer,money两种类型，整数，金额两种(支持两位小数)，
> maxLength 为允许输入的数字的最大长度；
其他属性属性请查看`http://element-cn.eleme.io/2.4/#/zh-CN/component/input`
