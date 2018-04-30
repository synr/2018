<h1 id="show_error_title">剛才的頁面，目前禁止訪問！</h1>
## 請你從正確管道取得相關權限，才能閱讀剛剛的頁面。

- 認證已失效，請重新從正確的入口進入。

<script type="text/javascript">
  localStorage['wm']='CC';
</script>
  
<script type="text/javascript">
  //2016.12.05+ 採集之前的錯誤頁面資訊做出提示。
  if(!((localStorage['error_md'] === undefined)||(localStorage['error_md'] == null)||(localStorage['error_md'] == ''))){
    document.getElementById('show_error_title').innerHTML = '剛才的頁面「' + localStorage['error_md'] + '」，目前禁止訪問！';
    if(!((localStorage['error_url'] === undefined)||(localStorage['error_url'] == null)||(localStorage['error_url'] == ''))){
        document.getElementById('show_error_title').innerHTML = '剛才的頁面「' + localStorage['error_md'] + '」，目前禁止訪問！';
        document.getElementById('show_error_title').innerHTML = '剛才的頁面「' + '<a href=\"' + localStorage['error_url'] +  '\" target=\"_blank\">' + localStorage['error_md'] +  '</a>' + '」，目前禁止訪問！';
    }
  }
  localStorage.removeItem('error_md');
  localStorage.removeItem('error_url');
</script>
