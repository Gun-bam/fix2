<template>
  <q-page class="row justify-center bg-grey-1">
    <div
      class="col-xl-5 col-lg-6 col-md-7 col-sm-8 col-xs-11"
      style="white-space: normal; font-size: 1rem"
    >
      <div class="q-py-lg text-h5 text-bold">군밤 개인정보처리방침</div>

      <!-- fixme 정보처리 버튼 -->
      <section class="btnNone">
        <div class="row">
          <q-btn
            class="col-4 btnFont mbFont"
            style="border: solid 1px grey"
            flat
            dense
            @click="goto('div1')"
            label="1. 개인정보 처리방침 >"
          />
          <q-btn
            class="col-4 btnFont mbFont"
            style="border: solid 1px grey"
            flat
            dense
            @click="goto('div2')"
            label="2. 개인정보 수집 >"
          />
          <q-btn
            class="col-4 btnFont mbFont"
            style="border: solid 1px grey"
            flat
            dense
            @click="goto('div3')"
            label="3. 개인정보 이용 >"
          />
        </div>
        <div class="row q-mt-xs">
          <q-btn
            class="col-4 btnFont mbFont"
            style="border: solid 1px grey"
            flat
            dense
            @click="goto('div4')"
            label="4. 개인정보 제공 >"
          />
          <q-btn
            class="col-4 btnFont mbFont"
            style="border: solid 1px grey"
            flat
            dense
            @click="goto('div5')"
            label="5. 개인정보 파기 >"
          />
          <q-btn
            class="col-4 btnFont mbFont"
            style="border: solid 1px grey"
            flat
            dense
            id="btn1"
            @click="goto('div6')"
            label="6. 기타사항 >"
          />
        </div>
        <br />
      </section>

      <!-- fixme 정보처리 방침 약관 내용 -->
      <section>
        <div ref="div1">
          <span class="text-bold">1. 개인정보 처리방침이란?<br /></span>
          <div class="q-pl-md">
            주식회사 군밤(이하"회사")는 이용자의 ‘동의를 기반으로 개인정보를
            수집·이용 및 제공’하고 있으며, ‘이용자의 권리 (개인정보
            자기결정권)를 적극적으로 보장’합니다.회사는 정보통신서비스제공자가
            준수하여야 하는 대한민국의 관계 법령 및 개인정보보호 규정,
            가이드라인을 준수하고 있습니다.“개인정보처리방침”이란 이용자의
            소중한 개인정보를 보호함으로써 이용자가 안심하고 서비스를 이용할 수
            있도록 회사가 준수해야 할 지침을 의미합니다.본 개인정보처리방침은
            회사가 제공하는 군밤계정 기반의 서비스(이하 ‘서비스'라 함)에
            적용됩니다.
          </div>
        </div>
        <br />

        <div ref="div2">
          <span class="text-bold">2. 개인정보 수집<br /></span>
          <div class="q-pl-md">
            서비스 제공을 위한 필요 최소한의 개인정보를 수집하고 있습니다.<br />
            회원 가입 시 또는 서비스 이용 과정에서 홈페이지 또는 개별
            어플리케이션이나 프로그램 등을 통해 아래와 같은 서비스 제공을 위해
            필요한 최소한의 개인정보를 수집하고 있습니다.<br /><br />

            <span class="text-bold">[군밤계정]<br /></span>

            필수<br />
            이메일, 비밀번호, 이름(닉네임), 프로필사진, 친구목록, 군밤톡
            전화번호(군밤톡 이용자의 경우에 한함), 연락처, 서비스 이용내역,
            서비스 내 구매 및 결제 내역<br /><br />

            선택<br />
            생년월일, 성별, 배송지정보(수령인명, 배송지 주소, 전화번호)<br /><br />

            <span class="text-bold">[본인인증 시]<br /></span>
            이름, 성별, 생년월일, 휴대폰번호, 통신사업자, 내/외국인 여부,
            암호화된 이용자 확인값(CI), 중복가입확인정보(DI))<br /><br />

            <span class="text-bold">[법정대리인 동의 시]<br /></span>
            법정대리인 정보(이름, 성별, 생년월일, 휴대폰번호, 통신사업자,
            내/외국인 여부, 암호화된 이용자 확인값(CI),
            중복가입확인정보(DI))[유료서비스 이용 시]<br />
            신용카드 결제 시: 카드번호(일부), 카드사명 등휴대전화번호 결제 시:
            휴대전화번호, 결제승인번호 등계좌이체 시: 예금주명, 계좌번호,
            계좌은행 등상품권 이용 시: 상품권 번호, 해당 사이트 아이디<br /><br />

            <span class="text-bold">[환불처리 시]<br /></span>
            계좌은행, 계좌번호, 예금주명, 이메일<br /><br />

            <span class="text-bold">[현금영수증 발행 시]<br /></span>
            휴대폰번호, 현금영수증 카드번호<br />

            일부 서비스에서는 특화된 여러 기능들을 제공하기 위해 ‘군밤계정’에서
            공통으로 수집하는 정보 이외에 이용자에게 동의를 받고 추가적인
            개인정보를 수집할 수 있습니다.<br />
            ● 필수정보란? : 해당 서비스의 본질적 기능을 수행하기 위한 정보<br />
            ● 선택정보란? : 보다 특화된 서비스를 제공하기 위해 추가 수집하는
            정보 (선택 정보를 입력하지 않은 경우에도 서비스 이용 제한은
            없습니다.)<br />

            개인정보를 수집하는 방법은 다음과 같습니다.<br />
            개인정보를 수집하는 경우에는 반드시 사전에 이용자에게 해당 사실을
            알리고 동의를 구하고 있으며, 아래와 같은 방법을 통해 개인정보를
            수집합니다.<br />
            ● 회원가입 및 서비스 이용 과정에서 이용자가 개인정보 수집에 대해
            동의를 하고 직접 정보를 입력하는 경우<br />
            ● 제휴 서비스 또는 단체 등으로부터 개인정보를 제공받은 경우<br />
            ● 고객센터를 통한 상담 과정에서 웹페이지, 메일, 팩스, 전화 등<br />
            ● 온·오프라인에서 진행되는 이벤트/행사 등 참여<br />

            서비스 이용 과정에서 이용자로부터 수집하는 개인정보는 아래와
            같습니다.<br />
            PC웹, 모바일 웹/앱 이용 과정에서 단말기정보(OS, 화면사이즈, 디바이스
            아이디, 폰기종, 단말기 모델명), IP주소, 쿠키, 방문일시,
            부정이용기록, 서비스 이용 기록 등의 정보가 자동으로 생성되어 수집될
            수 있습니다.서비스 간 제휴, 연계 등으로 제3자로부터 개인정보를
            제공받고 있습니다.
          </div>
        </div>
        <br />

        <div ref="div3">
          <span class="text-bold">3. 개인정보 이용<br /></span>
          <div class="q-pl-md">
            회원관리, 서비스 제공·개선, 신규 서비스 개발 등을 위해
            이용합니다.회원 가입 시 또는 서비스 이용 과정에서 홈페이지 또는 개별
            어플리케이션이나 프로그램 등을 통해 아래와 같이 서비스 제공을 위해
            필요한 최소한의 개인정보를 수집하고 있습니다.<br />
            ● 회원 식별/가입의사 확인, 본인/연령 확인, 부정이용 방지<br />
            ● 만 14세 미만 아동 개인정보 수집 시 법정 대리인 동의여부 확인, 법정
            대리인 권리행사 시 본인 확인<br />
            ● 이용자간 메시지 전송, 친구등록 및 친구추천 기능의 제공<br />
            ● 친구에게 활동내역을 알리거나 이용자 검색, 등록 등의 기능 제공<br />
            ● 신규 서비스 개발, 다양한 서비스 제공, 문의사항 또는 불만처리,
            공지사항 전달<br />
            ● 유료서비스 이용 시 컨텐츠 등의 전송이나 배송·요금 정산<br />
            ● 서비스의 원활한 운영에 지장을 주는 행위(계정 도용 및 부정 이용
            행위 등 포함)에 대한 방지 및 제재<br />
            ● 인구통계학적 특성과 이용자의 관심, 기호, 성향의 추정을 통한 맞춤형
            컨텐츠 추천 및 마케팅에 활용<br />
            ● 음성명령 처리 및 음성인식 향상, 개인화 서비스 제공<br />
            ● 서비스 이용 기록, 접속 빈도 및 서비스 이용에 대한 통계, 프라이버시
            보호 측면의 서비스 환경 구축, 서비스 개선에 활용
          </div>
        </div>
        <br />

        <div ref="div4">
          <span class="text-bold">4. 개인정보 제공<br /></span>
          <div class="q-pl-md">
            군밤는 이용자의 별도 동의가 있는 경우나 법령에 규정된 경우를
            제외하고는 이용자의 개인정보를 제3자에게 제공하지 않습니다.제3자
            서비스와의 연결을 위해 아래와 같이 개인정보를 제공하고 있습니다.<br />
            군밤는 이용자의 사전 동의 없이 개인정보를 제3자에게 제공하지
            않습니다. 다만, 이용자가 외부 제휴사 등의 서비스를 이용하기 위하여
            필요한 범위 내에서 이용자의 동의를 얻은 후에 개인정보를 제3자에게
            제공하고 있습니다.<br />
            서비스 제공을 위해 아래와 같은 업무를 위탁하고 있습니다.<br />
            서비스 제공에 있어 필요한 업무 중 일부를 외부 업체로 하여금
            수행하도록 개인정보를 위탁하고 있습니다. 그리고 위탁 받은 업체가
            관계 법령을 준수하도록 관리·감독하고 있습니다.
          </div>
        </div>
        <br />

        <div ref="div5">
          <span class="text-bold">5. 개인정보 파기<br /></span>
          <div class="q-pl-md">
            개인정보는 수집 및 이용목적이 달성되면 지체없이 파기하며, 절차 및
            방법은 아래와 같습니다.<br />
            전자적 파일 형태인 경우 복구 및 재생되지 않도록 안전하게 삭제하고,
            그 밖에 기록물, 인쇄물, 서면 등의 경우 분쇄하거나 소각하여
            파기합니다.<br />
            또한, 군밤는 ‘개인정보 유효기간제’에 따라 1년간 서비스를 이용하지
            않은 회원의 개인정보를 별도로 분리 보관 또는 삭제하고 있으며, 분리
            보관된 개인정보는 4년간 보관 후 지체없이 파기합니다.이 외에 법령에
            따라 일정기간 보관해야 하는 개인정보 및 해당 법령은 아래 표와
            같습니다.관계법령에 따른 개인정보 보관<br /><br />
          </div>
          <div class="text-bold mbText" style="border-bottom: solid 1px black">
            관계법령에 따른 개인정보 보관 자세히 보기
          </div>
          <div class="row text-weight-regular text-grey-9 btnFont mbFont">
            <div class="col-5 q-py-sm text-black text-center borderBottom">
              보존항목
            </div>
            <div class="col-5 q-py-sm text-black text-center borderCenter">
              근거법령
            </div>
            <div class="col-2 q-py-sm text-black text-center borderBottom">
              보존기간
            </div>

            <div class="col-5 q-py-md text-center borderBottom">
              계약 또는 청약철회 등에 관한 기록
            </div>
            <div class="col-5 q-py-sm text-center borderCenter2" />
            <div class="col-2 q-py-md text-center borderBottom">5년</div>

            <div class="col-5 q-py-md text-center borderBottom">
              대금결제 및 재화 등의 공급에 관한 기록
            </div>
            <div class="col-5 q-py-sm text-center borderCenter2">
              전자상거래 등에서의 소비자<br />보호에 관한 법률
            </div>
            <div class="col-2 q-py-md text-center borderBottom">5년</div>

            <div class="col-5 q-py-md text-center borderBottom">
              소비자의 불만 또는 분쟁처리에 관한 기록
            </div>
            <div class="col-5 q-py-sm text-center borderCenter2"></div>
            <div class="col-2 q-py-md text-center borderBottom">3년</div>

            <div class="col-5 q-py-md text-center borderBottom">
              표시/광고에 관한 기록
            </div>
            <div class="col-5 q-py-sm text-center borderCenter" />
            <div class="col-2 q-py-md text-center borderBottom">6개월</div>

            <div class="col-5 q-py-md text-center borderBottom">
              세법이 규정하는 모든 거래에 관한 장부 및 증빙서류
            </div>
            <div class="col-5 q-py-md text-center borderCenter">국세기본법</div>
            <div class="col-2 q-py-md text-center borderBottom">5년</div>

            <div class="col-5 q-py-md text-center borderBottom">
              전자금융 거래에 관한 기록
            </div>
            <div class="col-5 q-py-md text-center borderCenter">
              전자금융거래법
            </div>
            <div class="col-2 q-py-md text-center borderBottom">5년</div>

            <div class="col-5 q-py-md text-center borderBottom">
              서비스 방문 기록
            </div>
            <div class="col-5 q-py-md text-center borderCenter">
              통신비밀보호법
            </div>
            <div class="col-2 q-py-md text-center borderBottom">3개월</div>
          </div>
        </div>
        <br />

        <div ref="div6">
          <span class="text-bold">6. 기타<br /></span>
          <div class="q-pl-md">
            군밤는 여러분의 권리를 보호합니다.<br />
            이용자(만 14세 미만인 경우 법정 대리인)는 언제든지 자신의 개인정보를
            조회하거나 수정할 수 있으며, 수집・이용에 대한 동의 철회 또는 가입
            해지를 요청할 수 있습니다.보다 구체적으로는 서비스 내 설정을 통한
            회원정보 수정 기능이나 회원탈퇴 기능을 이용할 수 있고, 고객센터를
            통해 서면, 전화 또는 이메일로 요청하시면 지체 없이
            조치하겠습니다.개인정보의 오류에 대한 정정을 요청하신 경우 정정을
            완료하기 전까지 해당 개인정보를 이용 또는 제공하지 않습니다.또한,
            '온라인 맞춤형 광고 개인정보보호 가이드 라인'에 따른 이용자
            권리보호를 위한 페이지도 제공하고 있습니다.<br />

            웹기반 서비스의 제공을 위하여 쿠키를 이용하는 경우가 있습니다.
            쿠키는 보다 빠르고 편리한 웹사이트 사용을 지원하고 맞춤형 서비스를
            제공하기 위해 사용됩니다.<br /><br />

            <span class="text-bold">쿠키란?<br /></span>
            웹사이트를 운영하는데 이용되는 서버가 이용자의 브라우저에 보내는
            아주 작은 텍스트 파일로서 이용자 컴퓨터에 저장됩니다.<br /><br />

            <span class="text-bold">사용목적<br /></span>
            개인화되고 맞춤화된 서비스를 제공하기 위해서 이용자의 정보를
            저장하고 수시로 불러오는 쿠키를 사용합니다. 이용자가 웹사이트에
            방문할 경우 웹 사이트 서버는 이용자의 디바이스에 저장되어 있는
            쿠키의 내용을 읽어 이용자의 환경설정을 유지하고 맞춤화된 서비스를
            제공하게 됩니다. 쿠키는 이용자가 웹 사이트를 방문할 때, 웹 사이트
            사용을 설정한대로 접속하고 편리하게 사용할 수 있도록 돕습니다. 또한,
            이용자의 웹사이트 방문 기록, 이용 형태를 통해서 최적화된 광고 등
            맞춤형 정보를 제공하기 위해 활용됩니다.<br /><br />

            <span class="text-bold">쿠키 수집 거부<br /></span>
            쿠키에는 이름, 전화번호 등 개인을 식별하는 정보를 저장하지 않으며,
            이용자는 쿠키 설치에 대한 선택권을 가지고 있습니다. 따라서, 이용자는
            웹 브라우저에서 옵션을 설정함으로써 모든 쿠키를 허용하거나, 쿠키가
            저장될 때마다 확인을 거치거나, 모든 쿠키의 저장을 거부할 수도
            있습니다. 다만, 쿠키 설치를 거부할 경우 웹 사용이 불편해지며,
            로그인이 필요한 일부 서비스 이용에 어려움이 있을 수 있습니다.<br /><br />

            <span class="text-bold">설정 방법의 예<br /></span>
            ● 1) Internet Explorer의 경우<br />
            ● 웹 브라우저 상단의 도구 메뉴 > 인터넷 옵션 > 개인정보 > 설정<br />
            ● 2) Chrome의 경우<br />
            ● 웹 브라우저 우측의 설정 메뉴 > 화면 하단의 고급 설정 표시 >
            개인정보의 콘텐츠 설정 버튼 > 쿠키<br /><br />

            군밤는 이용자의 소중한 개인정보 보호를 위해 다음의 노력을 하고
            있습니다.<br />
            이용자의 개인정보를 가장 소중한 가치로 여기고 개인정보를 처리함에
            있어서 다음과 같은 노력을 다하고 있습니다.<br />
            ● 이용자의 개인정보를 암호화하고 있습니다.<br />
            이용자의 개인정보를 암호화된 통신구간을 이용하여 전송하고, 비밀번호
            등 중요정보는 암호화하여 보관하고 있습니다.<br />
            ● 해킹이나 컴퓨터 바이러스로부터 보호하기 위하여 노력하고
            있습니다.<br />
            해킹이나 컴퓨터 바이러스 등에 의해 이용자의 개인정보가 유출되거나
            훼손되는 것을 막기 위해 외부로부터 접근이 통제된 구역에 시스템을
            설치하고 있습니다.<br />
            해커 등의 침입을 탐지하고 차단할 수 있는 시스템을 설치하여 24시간
            감시하고 있으며, 백신 프로그램을 설치하여 시스템이 최신 악성코드나
            바이러스에 감염되지 않도록 노력하고 있습니다. 또한 새로운 해킹/보안
            기술에 대해 지속적으로 연구하여 서비스에 적용하고 있습니다.<br />
            ● 소중한 개인정보에 접근할 수 있는 사람을 최소화하고 있습니다.<br />
            개인정보를 처리하는 직원을 최소화 하며, 업무용 PC에서는 외부 인터넷
            서비스를 사용할 수 없도록 차단 하여 개인정보 유출에 대한 위험을
            줄이고 있습니다.<br />
            또한 개인정보를 보관하는 데이터베이스 시스템과 개인정보를 처리하는
            시스템에 대한 비밀번호의 생성과 변경, 그리고 접근할 수 있는 권한에
            대한 체계적인 기준을 마련하고 지속적인 감사를 실시하고 있습니다.<br />
            ● 임직원에게 이용자의 개인정보 보호에 대해 정기적인 교육을 실시하고
            있습니다.<br />
            개인정보를 처리하는 모든 임직원들을 대상으로 개인정보보호 의무와
            보안에 대한 정기적인 교육과 캠페인을 실시하고 있습니다.<br />
            ● 이용자 정보의 보호 활동 및 체계에 대해 국내 및 국제 인증 규격을
            충족하고 있습니다.<br />
            정보보호 및 개인정보보호 관리 체계에 대해 국내 및 국제 인증 심사
            규격 대비 충족 여부를 매년 독립된 심사 기관으로부터 검증을 받고
            개선의 기회를 마련하고 있습니다.<br /><br />

            군밤는 유럽연합 일반 개인정보보호법(General Data Protection
            Regulation) 및 각 회원국의 법률을 준수합니다.<br />
            유럽연합 내 이용자를 대상으로 서비스를 제공하는 경우, 아래 내용이
            적용될 수 있습니다.<br /><br />

            <span class="text-bold"
              >[개인정보 처리의 목적 및 처리근거]<br
            /></span>
            군밤는 수집한 개인정보를 "3. 개인정보의 이용"에 기재된 목적으로만
            이용하며, 사전에 이용자에게 해당 사실을 알리고 동의를 구하고
            있습니다.그리고 GDPR 등 적용되는 법률에 따라, 군밤는 아래 하나에
            해당하는 경우에 이용자의 개인정보를 처리할 수 있습니다.<br /><br />
            ● 정보주체의 동의<br />
            ● 정보주체와의 계약의 체결 및 이행을 위한 경우<br />
            ● 법적 의무사항 준수를 위한 경우<br />
            ● 정보주체의 중대한 이익을 위해 처리가 필요한 경우<br />
            ● 회사의 적법한 이익 추구를 위한 경우(정보주체의 이익과 권리 또는
            자유가 그 이익보다 중요한 경우는 제외)<br /><br />

            <span class="text-bold"
              >[유럽연합 내 이용자의 권리 보장]<br
            /></span>
            군밤는 "여러분의 권리를 보호합니다"에서 알린 바와 같이, 이용자의
            개인정보를 소중하게 보호합니다. GDPR 등 적용되는 법률에 따라,
            이용자는 자신의 개인정보를 다른 관리자에게 이전해 달라고 요청할 수
            있고, 자신의 정보 처리 거부를 요청 할 수 있습니다. 그리고 이용자는
            개인정보보호 권한 당국에 불만을 제기할 권리가 있습니다.또한, 군밤는
            이벤트 및 광고 등 마케팅을 제공하기 위해 개인정보를 활용할 수
            있으며, 사전에 이용자의 동의를 구하고 있습니다. 이용자는 원하지 않은
            경우 언제든지 동의를 철회할 수 있습니다.위와 관련한 요청사항은
            고객센터를 통해 서면, 전화 또는 이메일로 연락하시면 지체 없이
            조치하겠습니다.개인정보의 오류에 대한 정정을 요청하신 경우 정정을
            완료하기 전까지 해당 개인정보를 이용 또는 제공하지 않습니다.<br />

            개인정보보호와 관련해서 궁금하신 사항은?<br />
            서비스를 이용하면서 발생하는 모든 개인정보보호 관련 문의, 불만,
            조언이나 기타 사항은 개인정보 보호책임자 및 담당부서로 연락해 주시기
            바랍니다. 군밤는 여러분의 목소리에 귀 기울이고 신속하고 충분한
            답변을 드릴 수 있도록 최선을 다하겠습니다.<br /><br />

            <span class="text-bold">개인정보 보호책임자 및 담당부서<br /></span>
            ● 책임자: 000 (개인정보 보호책임자/DPO)<br />
            ● 담당부서: 개인정보보호파트<br />
            ● 문의 : 군밤 고객센터 : 0000-0000<br />
            ● 또한 개인정보가 침해되어 이에 대한 신고나 상담이 필요하신 경우에는
            아래 기관에 문의하셔서 도움을 받으실 수 있습니다.<br /><br />

            <span class="text-bold">개인정보침해 신고센터<br /></span>
            ● (국번없이)118<br />
            ● https://privacy.kisa.or.kr<br />
            대검찰청 사이버수사과<br />
            ● (국번없이)1301<br />
            ● cid@spo.go.kr<br />
            경찰청 사이버수사국<br />
            ● (국번없이)182<br />
            ● https://ecrm.cyber.go.kr<br /><br />

            <span class="text-bold"
              >개인정보처리방침이 변경되는 경우<br
            /></span>
            법률이나 서비스의 변경사항을 반영하기 위한 목적 등으로
            개인정보처리방침을 수정할 수 있습니다. 개인정보처리방침이 변경되는
            경우 군밤는 변경 사항을 게시하며, 변경된 개인정보처리방침은 게시한
            날로부터 7일 후부터 효력이 발생합니다.<br />
            다만, 수집하는 개인정보의 항목, 이용목적의 변경 등과 같이 이용자
            권리의 중대한 변경이 발생할 때에는 최소 30일 전에 미리
            알려드리겠습니다.<br />
            ● 공고일자: 2021년 00월 00일<br />
            ● 시행일자: 2021년 00월 00일<br />
            군밤는 이용자 여러분의 정보를 소중히 생각하며, 이용자가 더욱
            안심하고 서비스를 이용할 수 있도록 최선의 노력을 다할것을
            약속드립니다.<br />
          </div>
        </div>
        <br />

        <!-- fixme PageUpBtn -->
        <q-page-scroller expand :scroll-offset="300" :offset="[0, 0]">
          <q-btn class="q-ma-md" round icon="keyboard_arrow_up" size="md" />
        </q-page-scroller>
      </section>
    </div>
  </q-page>
</template>

<script>
import $ from "jquery";

export default {
  setup() {
    return {};
  },
  methods: {
    goto(refName) {
      let element = this.$refs[refName];
      let top = element.offsetTop;

      $("html").animate({ scrollTop: top }, 400);
    },
  },
};
</script>

<style>
.btnFont {
  font-size: 0.9rem;
}

.marginCenter {
  margin-right: 50px;
}

.borderBottom {
  border-bottom: solid 1px rgba(128, 128, 128, 0.45);
}

.borderCenter {
  border-bottom: solid 1px rgba(128, 128, 128, 0.45);
  border-right: solid 1px rgba(128, 128, 128, 0.45);
  border-left: solid 1px rgba(128, 128, 128, 0.45);
}

.borderCenter2 {
  border-right: solid 1px rgba(128, 128, 128, 0.45);
  border-left: solid 1px rgba(128, 128, 128, 0.45);
}

@media (max-width: 420px) {
  .mbFont {
    font-size: 0.6rem;
  }

  .mbText {
    font-size: 0.9rem;
  }

  /*.btnNone{*/
  /*  display: none;*/
  /*}*/
}
</style>
