# Details #

  * First, you need installed [FileMgr](http://www.precentral.net/homebrew-apps/filemgr-service) service on your phone. WebOS mojo applications can't access to files directly.

  * Select "Split exported files" in MojoTracker preferences. FileMGR (1.0.0) fails with writing files larger than about 50KB. We can't fix it, because FileMGR is close source...

  * Open Saved tracks page, click on track that you want export and select "Export".

  * Connect your phone to PC and copy exported files from root of internal memory.

  * If track is splited to more files ( `G*.gpx.001`, `G*.gpx.002`...) merge it with your favorite file manager (for example Total Commander for Windows or Krusader for Linux can merge files).
