# 1 翻译功能（WXmini-SR-Translation）
## 最初的假设：
- 用户选择目标语言，在输入框中输入文本，程序在输出框中输出结果。
## 常规：
1. 用户点击目标语言，可以在语言菜单中选择需要的语言进行语言的切换，点击菜单下方的确定按钮回到翻译页面。
2. 用户在输入框中手动输入或粘贴文本，程序自动识别用户输入文本的语言类型。
3. 用户点击翻译按键，程序在输出框中输出译文结果。
## 可能出现的问题：
1. 输入的文本中含有程序无法识别的语言或字符等。程序提示存在无法识别的内容，请尝试修改后重新输入。
2. 网络连接丢失，程序翻译失败，程序提示请检查网络后重试。 
## 其他活动：
1. 用户点击历史可以查看近期的翻译历史。
2. 程序默认的目标语言为英语。
## 完成时的系统状态：
1. 用户打开程序，显示翻译页面，可通过在输入框中输入文本进行翻译，默认目标语言为英语，可点击“到英文”更换目标语言的类型。
2. 用户输入完成后，点击“翻译”进行翻译，翻译的结果显示在输出框中。
3. 程序记录了用户的翻译历史，用户可通过点击“历史”进行查看。
# 2 语音识别功能（WXmini-SR-SpeechRecognition）
## 最初的假设：
- 用户希望通过语音进行输入功能。用户处于翻译主界面。
## 常规：
1. 用户点击语言输入按键，在获取用户的相应权限后系统开始录音，程序将语音文件转化为文本文件。
2. 语音输入的结果以文本的形式输出在输入框中，用户可检查输出的文本是否符合需求并选择是否更改。
3. 系统自动识别用户录入的语言并输出相应语言的文本。
## 可能出现的问题：
1. 语音输入模糊系统无法识别为文本。系统提示用户录音质量不好，请尝试重新录入。
2. 用户未授权麦克风权限。系统提示请开启相应麦克风权限后重试。
## 其他活动：
- 系统对用户的录音文件进行保护，不允许未授权的人进行访问，以保护用户的隐私。
## 完成时的系统状态：
1. 用户可以通过语音输入的方式进行输入操作。
2. 系统将用户的语音文件翻译为文本文件并以文本的方式输出在输入框中。
# 3 语音合成功能（WXmini-SR-SpeechSynthesis）
## 最初的假设：
- 用户希望通过语音的形式来输出文本内容。用户在输入并点击翻译之后，译文已出现在输出框中。
## 常规：
1. 用户进行正常翻译之后，点击语音输出按钮，系统进行语音合成将文本以语音的形式输出。
2. 用户可选择对输入的文本内容或输出的文本内容进行语音输出。
## 可能出现的问题：
1. 系统语音合成功能障碍，无法将文本文件转化为语音文件。
2. 系统未获得用户的扬声器权限导致语音文件无法输出。系统提示请授予扬声器权限。
3. 用户的扬声器功能等障碍导致语音文件无法输出。系统提示请检查扬声器。
## 其他活动：
- 系统可以调节输出的音量或语速，满足用户的不同需求。
## 完成时的系统状态：
1. 用户可以通过手动输入/粘贴/语音输入等方式进行输入，点击翻译后译文输出在文本框中。
2. 用户可以将输入的文本内容或输出的文本内容以语音的形式输出。
# 4第三方OCR功能（WXmini-SR-OCR）
## 最初的假设：
- 用户希望将图片中的文本识别为文字并进行翻译。用户处于翻译主界面。
## 常规：
1. 用户点击第三方OCR功能，可以上传图片对图片中的文本进行识别并翻译。
2. 上传图片的方式分为拍照与从相册选择两种。
3. 系统自动识别图片中的文本语言类型，并将识别结果输出到输入框中，用户可选择翻译其中内容。
## 可能出现的问题：
1. 用户未授权图库权限导致照片上传失败。系统提示请授予图库权限。
2. 用户未授权拍照权限导致拍照失败。系统提示请授予拍照权限。
3. 系统第三方OCR功能故障，导致对图片的识别失败，无法生成相应文字并输出。系统提示识别失败。
## 其他活动：
1. 上传图片后用户可进行图片编辑，可选择整张图片或截取图片的一部分进行翻译。
2. 系统应保护用户的相册隐私，防止未授权者进行查看等操作。
## 完成时的系统状态：
- 用户可通过第三方OCR功能识别照片中的文本并将其以文本的形式输出在输入框中，并可进行翻译功能。