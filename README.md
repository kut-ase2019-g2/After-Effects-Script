# After-Effects-Script
アフターエフェクトを操作するスクリプトです

# フォルダ構成
AE/

　├After_Effects_test.aep　%アフターエフェクトのプログラム
  
　├ExtendScript.jsx　%エクステンドスクリプトのプログラム
  
　├image/　%画像とタグデータを入れるディレクトリ
  
　│　├画像10枚
    
　│　└タグデータ.csv
    
　└effects_img/　%エフェクトに使っている画像を入れるディレクトリ
  
　　 &nbsp;├heart.png
    
　　 &nbsp;└onp_v2.png

# ファイルのパス変更
ExtendScriptでは特定のファイルを，そのファイルへのパスによって呼び出しているため，違うPCでは実行できません．

ExtendScript.jsxの1，7，21，54，194，219行目のパスを，コメントに書いてあるファイルの場所に通してください．
