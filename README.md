# utsb_encon_entry
UTSB団内アンコン／エントリー担当のためのリポジトリ（最終更新日：02/02/2019）

## はじめに
　このフォルダは筑波大学吹奏楽団の団内アンコンのエントリー担当が，とっても簡単にエントリーを開始できるようにサポートするものです．事実上の，この係の引継書類となります．最後まで一読されることをお勧めします．  
  このシステムは，ユーザーがWeb上で全てのエントリーを完了できるように導入されました．導入された2018年以前は，Excelファイルを用いて演奏団体責任者が提出する形でエントリーを行なっていました.しかし，エントリーにはPCが必須であり，係の管理も手間が多いため，エントリー方法を一新するに至りました．
  
* ユーザー：参加者，演奏者のこと
* 管理者：団内アンコンエントリー担当者
* 団体責任者：


## エントリー担当の仕事
* メーリスでの告知
* このシステムの整備
  * このシステムを新たなGoogleアカウントにコピーすること 


## 引継に当たって 
<b>エントリー係が行う業務は,例年変わりません</b>，基本的には，この資料に従うことで業務は完了すると考えられます．何か大きなエントリー方法の変更などがあった際は，このシステムの変更などが必要になるでしょう．もしお困りの場合は，37期吉澤(takataku.shako.11326@gmail.com)まで，ご相談ください．


## このフォルダについて
utsb_encon_entry  
  ┠ README.md (このファイル)  
  ┠ PROCEDURE.md #お仕事手順書 (これ超重要)  
  ┣ player_entry  
  ┃   ┠ README.md  
  ┃   ┗ player_entry.txt    
  ┃  
  ┣ band_entry  
  ┃   ┠ README.md  
  ┃   ┗ band_entry.txt  
  ┃  
  ┗ player_add  
      ┠ README.md  
      ┠ player_add_by_xlsx  
      ┠ player_add_by_form  
      ┗ player_add_by_myself  

# このシステムについて
## 目的
このシステムの目的は，
* 団内アンコンのエントリーをWeb上で行えること，管理できること．
* ユーザーが，このWeb上で1次エントリー，2次エントリーをできること．
* 管理者が，一括して全ての団体のエントリーを扱えるようにすること．

## 機能
1. 参加エントリー  
  参加者が，自分自身を登録する．(アカウント発行)-->演奏者IDが発行される．  
  
2. 演奏団体エントリー  
  参加者が，演奏団体を作成する．-->参加者は，演奏団体責任者になる
  
3. 演奏団体メンバー登録  
  3-1. ファイルによる演奏メンバー登録：団体責任者が、演奏者リストを.xlsxファイルで送信 （スマホ不可）  
  3-2. フォームからの演奏メンバー登録：団体責任者が、Google Formから最大25人まで１度に登録  
  3-3. 既存団体への参加登録：演奏者が、入りたい団体に自分で登録  

## 実装方法
このシステムは，すべてGoogle Driveから使用できるアプリケーションをプログラミングを元に使用して作成されています．
このシステムのプログラミング言語はGoogle Apps Scriptです．  
詳しい１つ１つの機能がどのように実装されているかについては,それぞれのファイルに詳細を記載しております．
