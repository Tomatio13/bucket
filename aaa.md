  復元方法

  分割されたアーカイブを元に戻すには：

  cat videos_split.tar.gz.* | tar xzf -

  または、まず結合してから展開：

  # 結合
  cat videos_split.tar.gz.* > videos.tar.gz

  # 展開
  tar xzf videos.tar.gz
