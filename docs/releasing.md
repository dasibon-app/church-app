# 새 버전 내는 순서 (관리자용)

1. `church-app.html` 안의 `APP_VERSION`, `APP_DATE`를 올립니다.
2. `CHANGELOG.md`와 `docs/설치와-업데이트.md`의 버전을 고칩니다. 매뉴얼에 영향이 있으면 `docs/사용매뉴얼.pdf`도 새로 만듭니다.
3. 커밋하고 `v1.0.2` 같은 태그를 붙입니다.
4. GitHub → Releases → Draft a new release
   - 태그 선택, 제목은 `v1.0.2`
   - 설명에 변경 내용과 "업데이트 전에 전체 백업을 받으세요" 한 줄
   - 첨부: `church-app.html`, `사용매뉴얼.pdf`
5. Publish release. Watch → Releases를 켠 사용자에게 알림이 갑니다.

※ 성도 정보가 들어간 파일이나 실제 화면 캡처는 저장소에 올리지 않습니다. 올리기 전에 `grep`으로 교회 이름·이름·이메일이 남아 있는지 확인하세요.
