# 高階處理器 (Processor)

在前一章當中，我們說明了「微處理器」的設計方式，在本章中、我們將說明「高階處理器」的設計方式。

與「微處理器」比起來，「高階處理器」除了指令寬度較大之外，能定址的記憶體空間通常也很大，而且會內建「記憶體管理單元」(Memory Management Unit, MMU) 與多層快取機制 (cache) 等等，這些都是為了充分發揮處理器的效能的設計，這也正是為何稱為「高階」處理器的原因。

在本章當中，我們將透過 cpu0 這個架構，給出一個「處理器」的簡易範例之後，就開始針對現今的高階處理器之結構進行探討，以便讓讀者在能清楚的理解現代高階處理器的設計原理與特性。



