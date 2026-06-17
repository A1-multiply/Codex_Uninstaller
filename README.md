# Codex_Uninstaller

Windows에서 Codex를 깔끔하게 삭제하는 단일 실행 파일입니다. `uninstall-codex.bat` 하나만 다운로드해서 실행하면 됩니다.

Codex_Uninstaller is a single-file Windows uninstaller for Codex. Download and run only `uninstall-codex.bat`.

## 사용법 / How to Use

1. GitHub에서 `uninstall-codex.bat` 파일을 다운로드합니다.  
   Download `uninstall-codex.bat` from GitHub.

2. `uninstall-codex.bat`을 더블클릭해서 실행한 뒤 Windows 관리자 권한 요청을 승인합니다.
   Double-click `uninstall-codex.bat`, then approve the Windows administrator prompt.

3. 메뉴에서 `1`을 입력하면 Codex 삭제를 진행합니다.  
   Type `1` to remove Codex.

4. 확인 문구가 나오면 `DELETE`를 정확히 입력합니다.  
   When asked to confirm, type `DELETE` exactly.

5. 나가려면 메뉴에서 `2`를 입력합니다.  
   Type `2` to exit.

## 메뉴 / Menu

`1` Codex 프로그램, 스킬, 설정, 캐시, 대화 기록 모두 삭제  
`1` Remove Codex program, skills, settings, cache, and chat data

`2` 나가기  
`2` Exit

## 안전 범위 / Safety Scope

이 도구는 Codex로 식별되는 알려진 경로와 정확한 Codex 패키지만 대상으로 합니다. 다른 Windows 프로그램을 전체 검색하거나 임의로 삭제하지 않습니다.

This tool targets only known Codex paths and exact Codex package IDs. It does not scan for or remove unrelated Windows programs.

`uninstall-codex.bat`은 더블클릭하면 자동으로 관리자 권한을 요청합니다. 관리자 권한으로 실행되면 Windows 앱 패키지로 등록된 Codex까지 삭제합니다.

When double-clicked, `uninstall-codex.bat` automatically asks for administrator permission. With administrator permission, it also removes Codex registered as a Windows app package.

## 파일 / Files

- `uninstall-codex.bat`: 단일 실행 파일입니다. PowerShell 삭제 로직이 내부에 포함되어 있어 별도 `.ps1` 파일이 필요 없습니다.
- `README.md`: 사용법 안내입니다.
- `LICENSE`: MIT 라이선스입니다.

## 라이선스 / License

MIT License
