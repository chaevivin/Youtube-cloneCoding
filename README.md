#Youtube clone coding

## Mobile First

요즘 모바일 시장이 확장됨에 따라 많은 기업들이 웹사이트를 디자인을 할 때 모바일을 먼저 고려한 후 어떻게 더 반응적으로 브라우저에 보여줄 수 있을 지 고려한다.

그래서 이번 프로젝트는 모바일 화면을 먼저 구현한 후, 그에 따라 브라우저 화면을 구현했다. 재배치는 1번.

# 구성

1. 헤더
2. 비디오 플레이어
3. 비디오 정보
   - 제목이 버튼을 누르면 3줄로 늘어남
4. 스크롤링이 가능한 부분 (비디오는 고정되어 있음)

# 레이아웃 구조

1. 헤더 (Youtube_header)
   - 유튜브 로고 (header_logo)
     - 아이콘 (logo_icon)
     - 텍스트 (logo_title)
   - 아이콘 박스 (header_iconBox)
     - 아이콘 1 (iconBox_1)
     - 아이콘 2 (iconBox_2)
2. 비디오 플레이어 (Youtube_videoPlayer)
3. 비디오 정보 (Youtube_info)
   - 비디오 메타데이터가 들어있는 박스 (info_metadata)
     - 해시태그 (metadata_hashtag)
       - li \* 3
     - 타이틀 박스 (metadata_title)
       - 타이틀 (title_text)
       - 버튼 (title_button)
     - view, date (metadata_viewAndDate)
   - 액션 버튼 박스 (info_actionButton)
     - 좋아요 (actionButton_like)
     - 싫어요 (actionButton_dislike)
     - share (actionButton_share)
     - save (actionButton_save)
     - report (actionButton_report)
   - 채널 정보 (info_channel)
     - 채널 메타데이터 (channel_metadata)
       - 이미지
       - 채널 이름
         - 이름 (metadata_name)
         - 구독자 수 (metadata_subscribers)
     - 채널 구독 버튼 (channel_name)
     - subscribe 버튼 (channel_subscribe)
4. 재생 목록 (Youtube_playlist)
   - 재생 목록 박스 3개 (playlist_items)
     - 동영상 썸네일 이미지 (item_thumbnail)
     - 동영상 정보 (item_info)
       - 동영상 제목 (info_title)
       - 채널 이름 (info_channel)
       - 조회수 (info_views)
     - 동영상 아이콘 (item_icon)
