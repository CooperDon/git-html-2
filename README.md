## 《HTML常用标签》

  1. a标签

     + 属性

       + href：

         + 网址
         + 路径：/a/b/c.html
         + 伪协议

       + target：指定在哪个窗口打开超链接

         + _blank：在新的页面打开
         + _top：在最顶层页面打开
         + _parent：在当前页面的上一层页面打开
         + _self：默认值，在当前页面打开

       + download

       + rel = noopener

         ```htm
         <div>
               <a href="//taobao.com">超链接</a>
               <a href="taglist.html">跳转至taglist.html</a>
               <a href="javascript:alert('ha');">JavaScript伪协议</a>
               <a href="#xxx">点击跳转至当前id名称的标签</a>
               <a href="mailto:2625166031@qq.com">发邮件给某某</a>
               <a href="tel:13593250979">打电话给某某</a>
         </div>
         ```

     + 作用

       + 跳转至外部页面
       + 内部锚点
       + 邮箱/电话

  2. table标签

     + thead表头
     + tbody表格主体内容
     + tfoot表格底部内容
     + th表头各项内容列表
     + tr行
     + td列

     ```html
     <div>
             <table>
                 <thead>
                     <tr>
                         <th></th>
                         <th>小明</th>
                         <th>晓红</th>
                         <th>小颖</th>
                     </tr>
                 </thead>
                 <tbody>
                     <tr>
                         <th>语文</th>
                         <td>30</td>
                         <td>60</td>
                         <td>90</td>
                     </tr>
                     <tr>
                         <th>数学</th>
                         <td>30</td>
                         <td>60</td>
                         <td>90</td>
                     </tr>
                     <tr>
                         <th>英语</th>
                         <td>30</td>
                         <td>60</td>
                         <td>90</td>
                     </tr>
                 </tbody>
                 <tfoot>
                     <tr>
                         <th>总分</th>
                         <td>90</td>
                         <td>180</td>
                         <td>270</td>
                     </tr>
                 </tfoot>
             </table>
         </div>
     ```

  3. img标签

     + 属性：

       + src：图片路径
       + alt：当图片加载失败时所显示的文字
       + height：设置图片高度(只设置高度时，图片宽高成比例缩放)
       + weight：设置图片宽度(只设置宽度时，图片宽高成比例缩放)

     + 作用

       + 发出get请求，展示一张图片

       ![请求1](https://i.loli.net/2021/08/03/p1ZtPfvLqdNBUxI.png)

       ![请求2](https://i.loli.net/2021/08/03/9JiAFjTtWdYfZ1n.png)

     + 响应式：max-width

       + css样式设置为max-width:100%时，图片可变为响应式

     + 事件：onload/onerror

       + 监听图片是否加载成功

