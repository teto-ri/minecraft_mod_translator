# minecraft Mod Korean Translator with PAPAGO API
## 파파고 API를 이용한 마인크래프트 자동 모드 번역기

`N Cloud`에서 직접 API 키를 발급받아 사용해주시기 바랍니다. 
[Papago N Cloud 링크](https://www.ncloud.com/product/aiService/papagoTranslation)
config.json -> Client ID, Secret Key 입력
  
# Requirements
1. commentjson>=0.9.0  
pip install commentjson

# 사용방법
1. **mod**폴더에 번역하고자 하는 jar 모드 파일을 넣습니다.
2. 번역하고자 하는 jar파일에는 `asset/모드이름/lang/en_us.json` 으로 되어있는 기존 영어 문자열 팩이 있어야합니다.
3. python main.py로 실행
4. **translated_mod**에 `ko_kr.json`이 추가되고 번역된 jar 모드 파일이 생성됩니다.
5. 수동으로 마인크래프트 모드 폴더에 넣거나 커스포지,모드린스 등 모드런처를 이용해 기존 모드를 빼고
   수정된 모드파일을 가져다 적용하세요.
6. 수정된 한글모드파일은 재배포 금지이므로 개인서버나 싱글로만 사용하세요.