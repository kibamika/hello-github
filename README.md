# hello-github
GitHubの機能を試すためのリポジトリです。  
Git連載記事の作業用のリポジトリです。  

### stock_crawler.py
株価をネットから取得するpythonスクリプト。  
デフォルトでは銘柄コード「1321」(日経225連動型上場投資信託)の株価を取得する。  
取得する株価は日単位の始値、高値、安値、終値、出来高で、  
その取得期間は、「2018年1月1日」～「このpythonスクリプトの実行日」まで。  
取得結果はexcelとして保存され(ファイル名「1321_from2018.xlsx」)、保存パスは実行時のカレントディレクトリ。  
ソースコード上にある「SECURITY_CODE」の値を1321以外に変更すると他の銘柄の株価も取得可能。  
取得期間も容易に変更可能である。  