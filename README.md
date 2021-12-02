# tf.keras를 사용한 Neural Style Transfer

<h2>Description</h2>
Neural style transfer은 콘텐츠 (content) 이미지와 (유명한 작가의 삽화와 같은) 스타일 참조 (style reference) 이미지를 이용하여, 콘텐츠 이미지의 콘텐츠는 유지하되 
스타일 참조 이미지의 화풍으로 채색한 것 같은 새로운 이미지를 생성하는 최적화 기술입니다.
<br>
<br>
<h2>Pre-requisite</h2>
<li>Google 계정</li>
<li>Google Chrome</li>
<br>
<h2>Usage</h2>
<li>git이 있는 경우 : git clone을 사용하여 원하는 경로에 해당 repository를 복사합니다.</li>
<li>git이 없는 경우 : Code > Download ZIP 메뉴를 선택하여 다운로드 받은 후 원하는 경로에 압축을 해제합니다.</li>
<li>구글 로그인 > 구글 드라이브 > Neural Style Transfer 폴더 생성 후 다운로드 받은 폴더 전체를 업로드 합니다.</li>
<li>neustyle_transfer.ipynb 를 열어 셀 하나씩 실행하여 결과를 확인합니다.(단축키는 Ctrl+Enter)</li>
<li>이미지 변경을 원할 경우, 구글 드라이브 상의 content 또는 style 경로에 이미지를 업로드 한 후 아래와 같이 코드를 변경 해 줍니다. </li>


``` python
# style_transfer.ipynb 의 이미지 경로 변경

content_path = '/content/drive/MyDrive/Neural_style_transfer/content/이미지파일명.확장자명'
style_path = '/content/drive/MyDrive/Neural_style_transfer/style/이미지파일명.확장자명'

```

<br>
<h2>Reference</h2>
<li>Leon A. Gatys의 논문인 <a href="https://arxiv.org/abs/1508.06576">A Neural Algorithm of Artistic Style</a></li>
<li><a href="https://www.tensorflow.org/tutorials/generative/style_transfer">Tensorflow Tutorial</a></li>
