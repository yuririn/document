# Linux操作
LinuxはOSのひとつ  
サーバで使われる  
CUI操作  
Character User Interface  

# 強制中断
  ctrl + c  
  実行中の処理を強制的に中断
# 現在地確認
  pwd  
  print working directory  
  今自分がいるパスを表示する  
  
# 移動
  cd 移動先  
  change dictory  
  cd ディレクトリ名 => 指定したディレクトリに移動  
  cd ~            => ユーザーのホームに移動  
  cd /            => ルートディレクトリに移動  
  cd ..           => 一個上に移動  
  
## Tabで入力補完

# ディレクトリ作成
  mkdir ディレクトリ名  
  make directory  

# 一覧表示
  ls  
  list  
  現在地直下のファイル一覧を表示  
  ls -a  
    隠しファイルを含めて表示  
  ls -l  
    リスト表示  
  ls -la  
    隠しファイルを含めて、リスト表示  
    
# 複製
  cp  
  copy  
  cp コピー元 コピー先ファイル名  

# ファイル移動  
  mv  
  move  
  mv 移動するファイル名 移動先ファイル名  
  ファイル名の変更にも利用する  
  
# ファイルの内容表示
  less  
  less ファイル名  
  閲覧モードになる  
  qを押すと終了してコマンド待機状態に戻る  
  
# ファイルの編集
  vim  
  vim 編集するファイル名  
  vim 新規作成するファイル名  
  閲覧モード => i 入力モードに  
  入力モード => esc 閲覧モードに  
  カーソルの移動  
    h => 左  
    j => 下  
    k => 上  
    l => 右  
    
  閲覧モード状態で
    :w    => 保存  
    :q    => 終了  
    :wq   => 保存して終了  
    :q!   => 強制終了(保存されない)  
    
# 削除
  rm  
  remove  
  rm ファイル名  
