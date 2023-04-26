# KH 파이널 프로젝트로 진행한 'LiClass' 입니다.

오프라인 원데이클래스 플랫폼을 구축해 보았습니다.
프로젝트는 총 6명에서 진행하였습니다.

제가 맡은 부분은 
1. 결제 시스템
    * 포인트 적립 (결제 금액의 3%)
    * 포인트 사용 (사용포인트만큼 차감하여 결제 진행)
2. 환불 시스템 
    * 포인트 사용 결제건 환불 시 포인트도 같이 환불
    * 환불 규정에 따라 환불 제어
      - 결제 후 7일 이후부터 환불 불가능
      - 예약일 하루 전부터 환불 불가능
3. 결제 내역 페이지
    * 유저의 모든 결제내역을 볼수 있는 페이지
4. 수강 내역 페이지
    * 수강 예정/완료 클래스를 볼수 있는 페이지
    * 수강내역 페이지에서 리뷰를 쓸수 있음 -> 예약일 당일부터 리뷰 쓸 수 있게 제어
5. 관리자 - 회원관리 페이지
    * 회원 강제 탈퇴기능 
    * 회원 삭제기능 (DB상에서 완전 삭제)


------------------------------------------------
참고사항 
    * LiClassProject.zip 은 프로젝트 자체 파일입니다.
    * sql은 산출물 안에 있습니다.

