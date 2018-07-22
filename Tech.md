## css:
scss
媒体查询


限制文本行数：
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    overflow: hidden;

多行省略显示：
      overflow: hidden;
      text-overflow: ellipsis;
      white-space: nowrap;
      //word-wrap: normal;