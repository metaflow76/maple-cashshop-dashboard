# 메이플스토리 캐시샵 DB 대시보드

메이플스토리 공식 캐시샵 공지(Sale/EndOfSale)를 Notion DB로 정리한 작업 현황 대시보드.

- **Notion DB**: https://www.notion.so/7d466f34c12349c2a6ed036993e3cb20
- **대시보드**: https://metaflow76.github.io/maple-cashshop-dashboard/

## 구성
- `index.html` — TailwindCDN 기반 정적 대시보드
- `data.json` — 판매 공지, 패키지, 이벤트 보상 요약 데이터
- 데이터 갱신 시 `data.json`만 수정하면 됨

## 로컬 미리보기
```bash
python -m http.server 8000
# http://localhost:8000
```

## GitHub Pages 배포
1. GitHub에 `maple-cashshop-dashboard` 레포 생성
2. `git remote add origin https://github.com/metaflow76/maple-cashshop-dashboard.git`
3. `git push -u origin main`
4. Settings → Pages → Source: `main` branch `/` root
