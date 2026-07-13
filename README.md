# 무브핏 — 체형교정 운동 코치 (프로토타입)

키·몸무게·목표를 입력하면 체형(BMI)·목표·부위에 맞는 운동/스트레칭을 유튜브 영상과 함께 추천하고,
완료할 때마다 경험치로 캐릭터가 성장하는 학생용 운동 코치 웹앱.

- 단일 정적 파일: `index.html`
- 기획/설계서: `체형교정_운동추천앱_기획설계서.md`

## 로컬에서 실행
```bash
python3 -m http.server 8000
# http://localhost:8000/
```
> 유튜브 임베드는 http(s) 환경에서만 재생됩니다. 파일을 그냥 더블클릭(`file://`)하면 영상이 안 나옵니다.

## 배포 (GitHub Pages)
GitHub 저장소에 올린 뒤 Settings → Pages에서 활성화하면
`https://<github-사용자명>.github.io/body-fit-app/` 로 공개됩니다.
