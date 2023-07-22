# 暑假实习项目

## AI生成图片

### 项目要求

+ 用stable diffusion产生中国，英国，俄国，法国，西班牙，葡萄牙，日本，阿拉伯国风格的男女模特或者地理风情的真实风格图片，总计80张（每个国家特色的10张），然后考虑人物的动画自动生成，包括语言对嘴型，以及各种情绪的动作和表情
+ 使用真实风格的模型



### tags设计

+ 中国风格：(Chinese),(female|male),(black hair),(brown eyes),(pale skin),(slim),(cheongsam|tang suit|hanfu|qipao|modern clothing),(jade|pearl|silver|gold),(fan|umbrella|lantern|flower),(pagoda|temple|palace|garden|mountain)
+ 英国风格：(British),(female|male),(blonde|brown|red hair),(blue|green|brown eyes),(fair skin),(tall),(suit|dress|coat|hat|scarf),(watch|ring|necklace|earrings),(umbrella|glasses|book|tea cup),(castle|church|bridge|park|city)
+ 俄国风格：(Russian),(female|male),(blonde|brown hair),(blue|green eyes),(fair skin),(strong),(fur coat|jacket|dress|boots),(hat|muffler|gloves),(balalaika|matryoshka doll|vodka bottle),(kremlin|cathedral|monument|forest|snow)
+ 法国风格：(French),(female|male),(brown|black hair),(brown|hazel eyes),(olive skin),(slender),(beret|scarf|dress|suit),(perfume|lipstick|earrings|rings),(baguette|wine bottle|cheese plate|( (Eiffel Tower))|( (Louvre))|( (Notre Dame))|( (Arc de Triomphe))
+ 西班牙风格：(Spanish),(female | male), (black | brown hair), (brown | hazel eyes), (tan skin), (curvy | muscular), (flamenco dress | shirt | pants | shoes), (flower | fan | shawl | earrings), (guitar | castanets | sangria glass), (( (Alhambra)) | (( (Sagrada Familia)) | (( (Plaza Mayor)) | (( (bullring)))
+ 葡萄牙风格：(Portuguese), (female | male), (black | brown hair), (brown | green eyes), (olive skin), (average height), (dress | shirt | skirt | pants), (necklace | bracelet | earrings | ring), (guitarra portuguesa | pastel de nata | wine glass | cork), (( (Belem Tower)) | (( (Jeronimos Monastery)) | (( (Pena Palace)) | (( (Porto Bridge)))
+ 日本风格：(Japanese), (female | male), (black hair), (brown eyes), (pale skin), (petite), (kimono | yukata | school uniform | cosplay), (hairpin | fan | umbrella | glasses), (sakura | sushi | sake cup | manga), (( (Mount Fuji)) | (( (Tokyo Tower)) | (( (Kyoto Temple)) | (( (Osaka Castle)))
+ 阿拉伯风格：(Arabic), (female | male), (black hair), (brown eyes), (tan skin), (slim), (abaya | hijab | niqab | thawb), (gold | silver | pearl | ruby), (hookah pipe | coffee pot | dates plate | sword), (( (pyramid)) | (( (mosque)) | (( (desert)) | (( (oasis)))



### 动画生成

+ 使用Inpaint工具，您可以在图像中标记出您想要移动的部分，然后生成多个变化的图像，然后将它们导入一个GIF或视频制作工具中，形成一个动画效果。
+ 使用Deforum扩展，您可以从头开始生成一种“变形”的动画，它会将一个图像逐渐变成另一个图像，并输出一个MP4视频文件，您还可以添加音频。
+ 