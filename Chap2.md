dim3 block(3);
dim3 grid((nElem+block.x-1)/block.x);
  你可能注意到grid的大小四舍五入是线程块
