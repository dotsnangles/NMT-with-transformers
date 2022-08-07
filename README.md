# NMT-with-transformers

### Logs
mT5-small Ko2En 기술과학/전체 [(WandB logs)](https://wandb.ai/dotsnangles/ko2en-translator-mt5-small-with-the-domain-data)  
mT5-small En2Ko 기술과학/전체 [(WandB logs)](https://wandb.ai/dotsnangles/en2ko-translator-mt5-small-with-the-domain-data)  
mT5-small En2Ko 기술과학/인공지능 [(WandB logs)](https://wandb.ai/dotsnangles/en2ko-translator-mt5-small)

### Main Packages  
Huggingface, Papermill, WandB, DVC

### Models  
[**mT5-small**](https://huggingface.co/google/mt5-small)  
[**mBART**](https://huggingface.co/facebook/mbart-large-50-many-to-many-mmt)  
Opus-MT  
Vanilla Transformer

### Tokenizer
SentencePiece

### Dataset  
[AIHub기술과학 분야 한영 번역 병렬 말뭉치 데이터](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=71266)

### Todos  
- [x] reformat data
- [x] write training code
- [x] connect to WandB
- [x] use Papermill if available
- [ ] ~utilize DVC if needed~
- [ ] ~apply effective augmentation methods if have time~
- [ ] understand SentencePiece and try it out with the data to pretrain a transformer model later
- [ ] try out the generation methods and understand how they work
- [ ] evaluate the finetuned models with BLUE Score
- [ ] come up with some ideas that can help translators work more efficiently utilizing transformer translators
