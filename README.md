# day12-15

### 进度条

    <div class="full">
      <div class="base"></div>
    </div>

    .full {
    width: 100%;
    height: 0.3rem;
    margin-top: 30px;
    background-color: #475364;
    border-radius: 2px;
    }
    .base {
    width: 18%;
    height: 100%;
    background: linear-gradient(to right, #7f5be6, #9d8fe3);
    border-radius: 2px;
    }

### 使部分滚动并隐藏滚动条
    .overflow {
      overflow: scroll;
    }

    .overflow::-webkit-scrollbar {
      display: none;
    }   
   * 注意计算高度要正确

### 图片添加蒙版Mask
- 要点:先把蒙版设置为 ` display:none;` 然后设置`:hover` 时` display：block;`
- 注意：高度和宽度要设置为100%
