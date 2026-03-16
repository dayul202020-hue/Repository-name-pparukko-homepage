export default function PparukkoHomepage() {
  const phone = "010-XXXX-XXXX"; // 실제 전화번호로 변경
  const logo = "/logo.png"; // public 폴더 기준 로고 경로
  const kakao = "https://open.kakao.com/"; // 카카오톡 상담 링크
  const instagram = "https://instagram.com/pparukko_demolition"; // 인스타 주소

  const services = [
    {
      title: "상가 철거",
      desc: "카페, 음식점, 매장 철거부터 집기 철거와 폐기물 처리까지 한 번에 진행합니다.",
    },
    {
      title: "사무실 철거 / 원상복구",
      desc: "칸막이, 바닥, 천장 철거와 임대 종료 전 원상복구 작업까지 깔끔하게 대응합니다.",
    },
    {
      title: "주택 철거",
      desc: "빌라, 원룸, 주택 내부 철거와 리모델링 전 철거 작업을 신속하게 진행합니다.",
    },
    {
      title: "부분 철거",
      desc: "벽체, 욕실, 바닥, 천장 등 필요한 부분만 선택해서 합리적으로 작업할 수 있습니다.",
    },
    {
      title: "폐기물 처리",
      desc: "철거 후 발생하는 폐기물 수거와 현장 정리까지 책임 있게 마무리합니다.",
    },
    {
      title: "철거 상담",
      desc: "현장 사진만 보내주셔도 빠르게 상담하고 작업 가능 여부와 대략 견적을 안내합니다.",
    },
  ];

  const strengths = [
    "직영 작업팀 운영",
    "현장 맞춤 견적",
    "빠른 일정 조율",
    "폐기물 처리까지 원스톱",
    "깔끔한 마감",
    "서울 · 경기 중심 대응",
  ];

  const steps = [
    ["01", "상담 접수", "전화 또는 카카오톡으로 상담을 접수합니다."],
    ["02", "현장 확인", "현장 방문 또는 사진 상담으로 작업 범위를 확인합니다."],
    ["03", "견적 안내", "작업 범위에 맞춰 빠르게 견적을 안내합니다."],
    ["04", "일정 협의", "원하시는 날짜에 맞춰 작업 일정을 조율합니다."],
    ["05", "철거 작업", "안전하게 철거 작업을 진행합니다."],
    ["06", "정리 및 마감", "폐기물 처리와 현장 정리까지 깔끔하게 마무리합니다."],
  ];

  const cases = [
    {
      title: "시흥 카페 철거 25평",
      subtitle: "카페 집기 철거 · 내부 철거 · 폐기물 처리",
    },
    {
      title: "정왕동 사무실 원상복구 40평",
      subtitle: "칸막이 철거 · 바닥 정리 · 마감 정리",
    },
    {
      title: "배곧 상가 철거 18평",
      subtitle: "매장 철거 · 간판 철거 · 내부 정리",
    },
  ];

  const gallery = [
    "철거 전 현장",
    "내부 철거 진행",
    "폐기물 정리",
    "원상복구 마감",
    "상가 철거 완료",
    "사무실 철거 완료",
  ];

  const seoRegions = [
    "서울 철거",
    "경기 철거",
    "서울 상가 철거",
    "경기 상가 철거",
    "서울 사무실 철거",
    "경기 사무실 철거",
    "서울 원상복구",
    "경기 원상복구",
  ];

  const estimateTypes = [
    { name: "상가 철거", base: 18 },
    { name: "사무실 철거 / 원상복구", base: 16 },
    { name: "주택 철거", base: 15 },
    { name: "부분 철거", base: 10 },
  ];

  return (
    <div className="min-h-screen bg-neutral-950 text-white">
      <section className="relative overflow-hidden border-b border-yellow-500/20 bg-gradient-to-br from-neutral-950 via-neutral-900 to-black">
        <div className="absolute inset-0">
          <div className="absolute -left-16 top-8 h-72 w-72 rounded-full bg-yellow-500/20 blur-3xl" />
          <div className="absolute right-0 top-0 h-80 w-80 rounded-full bg-orange-500/10 blur-3xl" />
          <div className="absolute bottom-0 left-1/3 h-64 w-64 rounded-full bg-yellow-300/10 blur-3xl" />
        </div>

        <div className="relative mx-auto max-w-7xl px-6 py-6 lg:px-10">
          <div className="flex items-center justify-between rounded-2xl border border-white/10 bg-white/5 px-4 py-3 backdrop-blur">
            <div className="flex items-center gap-3">
              <div className="flex h-11 items-center rounded-xl bg-white px-3 py-2 shadow-sm">
                <img src={logo} alt="빠루꼬 철거 로고" className="h-7 w-auto object-contain" onError={(e)=>{e.currentTarget.style.display='none'; e.currentTarget.parentElement.innerHTML='<span style="font-weight:800;color:#f2c544">빠루꼬</span>';}} />
              </div>
              <div>
                <div className="text-xl font-black tracking-tight">빠루꼬 철거</div>
                <div className="text-xs text-neutral-400">PPARUKKO DEMOLITION</div>
              </div>
            </div>
            <div className="hidden gap-3 md:flex">
              <a href="#services" className="text-sm text-neutral-300 hover:text-white">서비스</a>
              <a href="#process" className="text-sm text-neutral-300 hover:text-white">진행 과정</a>
              <a href="#cases" className="text-sm text-neutral-300 hover:text-white">작업 사례</a>
              <a href="#contact" className="text-sm text-neutral-300 hover:text-white">문의하기</a>
            </div>
          </div>
        </div>

        <div className="relative mx-auto grid max-w-7xl gap-12 px-6 pb-20 pt-10 lg:grid-cols-2 lg:px-10 lg:pb-28 lg:pt-16">
          <div className="flex flex-col justify-center">
            <div className="mb-5 inline-flex w-fit rounded-full border border-yellow-400/30 bg-yellow-400/10 px-4 py-1 text-sm font-semibold text-yellow-300">
              서울 · 경기 전지역 철거 전문
            </div>

            <h1 className="text-4xl font-black leading-tight tracking-tight sm:text-5xl lg:text-6xl">
              철거는 시원하게<br />
              <span className="text-yellow-400">마무리는 깔끔하게</span>
            </h1>

            <p className="mt-6 max-w-2xl text-base leading-7 text-neutral-300 sm:text-lg">
              빠루꼬 철거는 상가, 사무실, 주택 철거와 원상복구를 전문으로 합니다.
              현장 상황에 맞는 맞춤 견적과 책임 있는 마감으로 빠르고 깔끔하게 대응합니다.
            </p>

            <div className="mt-8 flex flex-wrap gap-3">
              <a
                href={`tel:${phone}`}
                className="rounded-2xl bg-yellow-400 px-6 py-3 text-sm font-black text-black shadow-lg shadow-yellow-500/20 transition hover:-translate-y-0.5"
              >
                전화 상담
              </a>
              <a
                href={kakao}
                className="rounded-2xl border border-yellow-400/30 bg-yellow-400/10 px-6 py-3 text-sm font-black text-yellow-300 transition hover:bg-yellow-400/20"
              >
                카카오톡 상담
              </a>
              <a
                href="#contact"
                className="rounded-2xl border border-white/20 bg-white/5 px-6 py-3 text-sm font-black text-white transition hover:bg-white/10"
              >
                무료 견적 문의
              </a>
            </div>

            <div className="mt-8 grid gap-3 sm:grid-cols-3">
              {[
                "직영 작업팀 운영",
                "빠른 일정 조율",
                "현장 사진 빠른 상담",
              ].map((item) => (
                <div key={item} className="rounded-2xl border border-white/10 bg-white/5 p-4 text-sm text-neutral-200">
                  {item}
                </div>
              ))}
            </div>
          </div>

          <div className="flex items-center justify-center">
            <div className="w-full rounded-[2rem] border border-white/10 bg-neutral-900/80 p-6 shadow-2xl shadow-black/40 backdrop-blur">
              <div className="grid gap-4 md:grid-cols-2">
                <div className="rounded-[1.5rem] border border-yellow-400/20 bg-gradient-to-br from-neutral-800 to-neutral-950 p-6 md:col-span-2">
                  <div className="flex items-center gap-4">
                    <div className="flex items-center rounded-2xl bg-white px-4 py-3 shadow-sm">
                    <img src={logo} alt="빠루꼬 철거 로고" className="h-10 w-auto object-contain" onError={(e)=>{e.currentTarget.style.display='none'; e.currentTarget.parentElement.innerHTML='<span style="font-weight:800;color:#f2c544">빠루꼬</span>';}} />
                  </div>
                    <div>
                      <div className="text-2xl font-black">빠루꼬 철거</div>
                      <div className="text-sm text-neutral-400">상가 · 사무실 · 주택 철거 전문</div>
                    </div>
                  </div>
                  <p className="mt-5 text-sm leading-6 text-neutral-300">
                    원상복구 / 부분철거 / 폐기물 처리까지 한 번에.
                    현장 사진을 보내주시면 보다 빠르게 상담 가능합니다.
                  </p>
                </div>

                <div className="rounded-[1.5rem] border border-white/10 bg-black/20 p-5">
                  <div className="text-sm text-yellow-300">빠른 문의</div>
                  <div className="mt-2 text-lg font-bold">전화 · 카카오톡 상담</div>
                  <p className="mt-2 text-sm leading-6 text-neutral-400">
                    급한 현장 문의도 빠르게 확인하고 대응합니다.
                  </p>
                </div>

                <div className="rounded-[1.5rem] border border-white/10 bg-black/20 p-5">
                  <div className="text-sm text-yellow-300">주요 지역</div>
                  <div className="mt-2 text-lg font-bold">서울 · 경기</div>
                  <p className="mt-2 text-sm leading-6 text-neutral-400">
                    서울 · 경기 전지역 현장 상담 및 작업 대응.
                  </p>
                </div>

                <div className="rounded-[1.5rem] border border-dashed border-yellow-400/30 bg-yellow-400/5 p-5 md:col-span-2">
                  <div className="text-sm font-bold text-yellow-300">문의 팁</div>
                  <p className="mt-2 text-sm leading-6 text-neutral-300">
                    현장 사진, 평수, 위치를 함께 보내주시면 더 정확하고 빠른 견적 안내가 가능합니다.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="services" className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
        <div className="mb-10 max-w-2xl">
          <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Service</p>
          <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">제공 서비스</h2>
          <p className="mt-3 text-neutral-400">
            빠루꼬 철거는 다양한 현장 경험을 바탕으로 철거부터 정리까지 책임 있게 진행합니다.
          </p>
        </div>

        <div className="grid gap-5 md:grid-cols-2 xl:grid-cols-3">
          {services.map((service) => (
            <div key={service.title} className="rounded-[1.75rem] border border-white/10 bg-white/5 p-6 shadow-lg shadow-black/20">
              <div className="mb-4 inline-flex rounded-xl bg-yellow-400/10 px-3 py-1 text-xs font-bold text-yellow-300">
                빠루꼬 철거
              </div>
              <h3 className="text-xl font-bold">{service.title}</h3>
              <p className="mt-3 text-sm leading-6 text-neutral-400">{service.desc}</p>
            </div>
          ))}
        </div>
      </section>

      <section className="border-y border-white/10 bg-neutral-900/60">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10">
          <div className="grid gap-10 lg:grid-cols-[1.2fr_1fr]">
            <div>
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Why Us</p>
              <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">왜 빠루꼬 철거인가</h2>
              <p className="mt-4 max-w-2xl text-neutral-400">
                철거업은 속도도 중요하지만 마감이 더 중요합니다. 빠루꼬 철거는 현장 상황에 맞는
                작업 방식과 깔끔한 정리까지 포함해 신뢰를 드리는 것을 목표로 합니다.
              </p>
            </div>
            <div className="grid gap-4 sm:grid-cols-2">
              {strengths.map((item) => (
                <div key={item} className="rounded-2xl border border-yellow-400/20 bg-yellow-400/5 p-5 text-sm font-medium text-neutral-100">
                  {item}
                </div>
              ))}
            </div>
          </div>
        </div>
      </section>

      <section id="process" className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
        <div className="mb-10 max-w-2xl">
          <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Process</p>
          <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">작업 진행 과정</h2>
        </div>

        <div className="grid gap-5 md:grid-cols-2 xl:grid-cols-3">
          {steps.map(([num, title, desc]) => (
            <div key={num} className="rounded-[1.75rem] border border-white/10 bg-gradient-to-b from-white/5 to-white/[0.03] p-6">
              <div className="text-sm font-black text-yellow-400">{num}</div>
              <div className="mt-2 text-xl font-bold">{title}</div>
              <p className="mt-3 text-sm leading-6 text-neutral-400">{desc}</p>
            </div>
          ))}
        </div>
      </section>

      <section id="cases" className="border-t border-white/10 bg-neutral-900/50">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="mb-10 max-w-2xl">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Work Cases</p>
            <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">작업 사례</h2>
            <p className="mt-3 text-neutral-400">
              실제 현장 사진을 넣으면 신뢰도가 더 높아집니다. 철거 전, 철거 중, 철거 후 사진을 함께 올리면 좋습니다.
            </p>
          </div>

          <div className="grid gap-6 lg:grid-cols-[1.1fr_1fr]">
            <div className="space-y-4">
              {cases.map((item) => (
                <div key={item.title} className="rounded-[1.75rem] border border-white/10 bg-white/5 p-6">
                  <div className="text-xl font-bold">{item.title}</div>
                  <div className="mt-2 text-sm text-neutral-400">{item.subtitle}</div>
                </div>
              ))}
            </div>

            <div className="grid gap-4 sm:grid-cols-2">
              {["철거 전", "철거 중", "철거 후", "원상복구 완료"].map((label, idx) => (
                <div key={label} className="group relative overflow-hidden rounded-[1.75rem] border border-white/10 bg-neutral-800 p-5 min-h-[190px]">
                  <div className="absolute inset-0 bg-gradient-to-br from-yellow-500/10 via-transparent to-orange-500/10 transition group-hover:scale-105" />
                  <div className="relative flex h-full flex-col justify-between">
                    <div className="inline-flex w-fit rounded-xl bg-black/40 px-3 py-1 text-xs font-bold text-yellow-300">
                      CASE {idx + 1}
                    </div>
                    <div>
                      <div className="text-xl font-bold">{label}</div>
                      <p className="mt-2 text-sm leading-6 text-neutral-400">
                        실제 작업 사진을 이 영역에 넣어 전후 비교형으로 보여주세요.
                      </p>
                    </div>
                  </div>
                </div>
              ))}
            </div>
          </div>
        </div>
      </section>

      <section className="border-t border-white/10 bg-neutral-950/70">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="mb-10 max-w-2xl">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Calculator</p>
            <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">간편 철거 견적 계산기</h2>
            <p className="mt-3 text-neutral-400">
              아래 내용은 대략적인 참고용입니다. 실제 금액은 현장 상태, 엘리베이터 유무, 폐기물 양, 마감 상태에 따라 달라질 수 있습니다.
            </p>
          </div>

          <div className="grid gap-6 lg:grid-cols-[1.1fr_0.9fr]">
            <div className="rounded-[2rem] border border-white/10 bg-white/5 p-8">
              <div className="grid gap-4 md:grid-cols-2">
                {estimateTypes.map((item) => (
                  <div key={item.name} className="rounded-2xl border border-white/10 bg-neutral-950/80 p-5">
                    <div className="text-lg font-bold">{item.name}</div>
                    <div className="mt-2 text-sm text-neutral-400">기준 단가: 평당 {item.base}만원부터</div>
                  </div>
                ))}
              </div>
              <div className="mt-6 rounded-2xl border border-dashed border-yellow-400/30 bg-yellow-400/5 p-5 text-sm leading-6 text-neutral-300">
                예시 계산법: 상가 철거 20평 × 평당 18만원 = 약 360만원부터
                <br />
                현장 사진을 보내주시면 보다 정확한 견적 상담이 가능합니다.
              </div>
            </div>

            <div className="rounded-[2rem] border border-yellow-400/20 bg-yellow-400/5 p-8">
              <div className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Quick Guide</div>
              <h3 className="mt-3 text-2xl font-black">견적 확인 순서</h3>
              <div className="mt-5 space-y-4 text-sm leading-6 text-neutral-300">
                <div>1. 철거 종류 확인</div>
                <div>2. 대략 평수 확인</div>
                <div>3. 현장 사진 촬영</div>
                <div>4. 전화 또는 카카오톡으로 상담</div>
              </div>
              <div className="mt-6 flex flex-wrap gap-3">
                <a href={`tel:${phone}`} className="rounded-2xl bg-yellow-400 px-5 py-3 text-sm font-black text-black">
                  바로 전화하기
                </a>
                <a href={kakao} className="rounded-2xl border border-yellow-400/30 bg-yellow-400/10 px-5 py-3 text-sm font-black text-yellow-300">
                  카카오톡 상담
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="contact" className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
        <div className="grid gap-6 lg:grid-cols-[1fr_1.1fr]">
          <div className="rounded-[2rem] border border-yellow-400/20 bg-yellow-400/5 p-8">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Contact</p>
            <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">무료 견적 문의</h2>
            <p className="mt-4 text-neutral-300">
              서울 · 경기 전지역에서 상가 철거, 사무실 철거, 원상복구 문의를 받고 있습니다.
              현장 사진을 보내주시면 보다 빠르게 상담 가능합니다.
            </p>
            <div className="mt-6 space-y-3 text-sm text-neutral-200">
              <div>전화: {phone}</div>
              <div>카카오톡: 상담 링크 연결</div>
              <div>인스타그램: @pparukko_demolition</div>
            </div>
            <div className="mt-6 flex flex-wrap gap-3">
              <a href={`tel:${phone}`} className="rounded-2xl bg-yellow-400 px-5 py-3 text-sm font-black text-black">
                바로 전화하기
              </a>
              <a href={kakao} className="rounded-2xl border border-yellow-400/30 bg-yellow-400/10 px-5 py-3 text-sm font-black text-yellow-300">
                카카오톡 문의
              </a>
            </div>
          </div>

          <div className="rounded-[2rem] border border-white/10 bg-white/5 p-8">
            <div className="grid gap-4 sm:grid-cols-2">
              <input className="rounded-2xl border border-white/10 bg-neutral-950 px-4 py-3 outline-none placeholder:text-neutral-500" placeholder="이름" />
              <input className="rounded-2xl border border-white/10 bg-neutral-950 px-4 py-3 outline-none placeholder:text-neutral-500" placeholder="연락처" />
              <input className="rounded-2xl border border-white/10 bg-neutral-950 px-4 py-3 outline-none placeholder:text-neutral-500 sm:col-span-2" placeholder="현장 위치" />
              <input className="rounded-2xl border border-white/10 bg-neutral-950 px-4 py-3 outline-none placeholder:text-neutral-500" placeholder="철거 종류" />
              <input className="rounded-2xl border border-white/10 bg-neutral-950 px-4 py-3 outline-none placeholder:text-neutral-500" placeholder="예상 평수" />
              <input className="rounded-2xl border border-white/10 bg-neutral-950 px-4 py-3 outline-none placeholder:text-neutral-500 sm:col-span-2" placeholder="희망 일정" />
              <textarea className="min-h-[130px] rounded-2xl border border-white/10 bg-neutral-950 px-4 py-3 outline-none placeholder:text-neutral-500 sm:col-span-2" placeholder="기타 요청사항 또는 현장 설명" />
            </div>
            <button className="mt-5 w-full rounded-2xl bg-yellow-400 px-6 py-4 text-sm font-black text-black transition hover:-translate-y-0.5">
              견적 문의 보내기
            </button>
            <p className="mt-3 text-xs leading-5 text-neutral-500">
              실제 사용 시에는 아임웹 문의폼 또는 외부 폼 연동 기능으로 연결하면 됩니다.
            </p>
          </div>
        </div>
      </section>

            {/* FAQ 섹션 */}
      <section className="border-t border-white/10 bg-neutral-900/40">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="mb-10 max-w-2xl">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">FAQ</p>
            <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">자주 묻는 질문</h2>
            <p className="mt-3 text-neutral-400">철거 상담 시 가장 많이 문의하시는 내용입니다.</p>
          </div>

          <div className="grid gap-6 md:grid-cols-2">
            <div className="rounded-2xl border border-white/10 bg-white/5 p-6">
              <div className="font-bold">Q. 철거 견적은 어떻게 받나요?</div>
              <p className="mt-2 text-sm text-neutral-400">현장 사진, 위치, 평수를 보내주시면 빠르게 견적 상담 가능합니다.</p>
            </div>

            <div className="rounded-2xl border border-white/10 bg-white/5 p-6">
              <div className="font-bold">Q. 철거 작업 기간은 얼마나 걸리나요?</div>
              <p className="mt-2 text-sm text-neutral-400">현장 규모에 따라 다르지만 일반 상가 철거는 보통 하루~2일 정도 소요됩니다.</p>
            </div>

            <div className="rounded-2xl border border-white/10 bg-white/5 p-6">
              <div className="font-bold">Q. 폐기물 처리도 같이 가능한가요?</div>
              <p className="mt-2 text-sm text-neutral-400">네 가능합니다. 철거 후 발생하는 폐기물 처리까지 함께 진행합니다.</p>
            </div>

            <div className="rounded-2xl border border-white/10 bg-white/5 p-6">
              <div className="font-bold">Q. 서울·경기 외 지역도 가능한가요?</div>
              <p className="mt-2 text-sm text-neutral-400">현장 위치에 따라 상담 후 작업 진행이 가능합니다.</p>
            </div>
          </div>
        </div>
      </section>

      {/* 견적 예시 섹션 */}
      <section className="border-t border-white/10 bg-neutral-950/60">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="mb-10 max-w-2xl">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Estimate</p>
            <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">철거 견적 예시</h2>
            <p className="mt-3 text-neutral-400">현장 상황에 따라 가격은 달라질 수 있습니다.</p>
          </div>

          <div className="grid gap-6 md:grid-cols-3">
            <div className="rounded-2xl border border-white/10 bg-white/5 p-6">
              <div className="font-bold text-lg">소형 매장 철거</div>
              <p className="text-sm text-neutral-400 mt-2">약 10~20평 매장</p>
              <div className="text-yellow-400 font-black mt-4">견적 상담</div>
            </div>

            <div className="rounded-2xl border border-white/10 bg-white/5 p-6">
              <div className="font-bold text-lg">카페 / 음식점 철거</div>
              <p className="text-sm text-neutral-400 mt-2">20~40평 매장</p>
              <div className="text-yellow-400 font-black mt-4">견적 상담</div>
            </div>

            <div className="rounded-2xl border border-white/10 bg-white/5 p-6">
              <div className="font-bold text-lg">사무실 원상복구</div>
              <p className="text-sm text-neutral-400 mt-2">칸막이 / 바닥 철거</p>
              <div className="text-yellow-400 font-black mt-4">견적 상담</div>
            </div>
          </div>
        </div>
      </section>

            {/* 영상 섹션 */}
      <section className="border-t border-white/10 bg-black/40">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="mb-10 max-w-2xl">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Video</p>
            <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">철거 작업 영상</h2>
            <p className="mt-3 text-neutral-400">
              작업 영상은 사진보다 현장감을 더 잘 전달합니다. 인스타 릴스, 유튜브 쇼츠, 작업 영상을 연결해 신뢰도를 높일 수 있습니다.
            </p>
          </div>

          <div className="grid gap-6 lg:grid-cols-[1.2fr_1fr]">
            <div className="rounded-[2rem] border border-white/10 bg-white/5 p-6">
              <div className="rounded-[1.5rem] border border-white/10 bg-neutral-950 min-h-[320px] flex items-center justify-center text-center text-neutral-400 p-6">
                유튜브 영상 / 인스타 릴스 / 작업 영상 삽입 영역
              </div>
              <p className="mt-4 text-sm text-neutral-400">
                실제 배포 시 유튜브 iframe 또는 인스타 영상 링크를 연결하면 됩니다.
              </p>
            </div>

            <div className="space-y-4">
              {[
                ["매장 철거 영상", "카페 · 음식점 · 상가 철거 현장 영상"],
                ["사무실 철거 영상", "칸막이 철거 · 바닥 철거 · 원상복구 영상"],
                ["폐기물 처리 영상", "정리 과정과 마감까지 보여주는 작업 영상"],
              ].map(([title, desc]) => (
                <div key={title} className="rounded-[1.5rem] border border-white/10 bg-white/5 p-5">
                  <div className="text-lg font-bold">{title}</div>
                  <p className="mt-2 text-sm leading-6 text-neutral-400">{desc}</p>
                </div>
              ))}
            </div>
          </div>
        </div>
      </section>

      {/* PARTNERS 모집 섹션 */}
      <section className="border-t border-white/10 bg-neutral-950">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="mb-10 max-w-2xl">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Partners</p>
            <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">파트너스 모집</h2>
            <p className="mt-3 text-neutral-400">
              서울 · 경기 지역 부동산 중개사 및 인테리어 업체와 협업 파트너를 모집합니다.
              철거 및 원상복구가 필요한 현장을 연결해 주시면 빠른 견적과 작업 진행이 가능합니다.
            </p>
          </div>

          <div className="grid gap-6 md:grid-cols-2">
            <div className="rounded-[1.75rem] border border-white/10 bg-white/5 p-6">
              <h3 className="text-xl font-bold">부동산 중개사 협업</h3>
              <p className="mt-3 text-sm text-neutral-400 leading-6">
                상가 임대 종료 시 원상복구 철거가 필요한 경우 빠르게 대응합니다.
                중개사분들이 연결해 주시는 현장은 신속 견적 및 일정 협의 가능합니다.
              </p>
              <ul className="mt-4 space-y-2 text-sm text-neutral-300">
                <li>• 상가 원상복구 철거</li>
                <li>• 임대 종료 철거</li>
                <li>• 공실 정리 및 내부 철거</li>
                <li>• 철거 견적 빠른 상담</li>
              </ul>
            </div>

            <div className="rounded-[1.75rem] border border-white/10 bg-white/5 p-6">
              <h3 className="text-xl font-bold">인테리어 · 시공 협업</h3>
              <p className="mt-3 text-sm text-neutral-400 leading-6">
                인테리어 공사 전 철거 작업을 전문적으로 지원합니다.
                철거 → 인테리어 공사 연결 구조로 협업 가능합니다.
              </p>
              <ul className="mt-4 space-y-2 text-sm text-neutral-300">
                <li>• 인테리어 전 철거</li>
                <li>• 부분 철거</li>
                <li>• 폐기물 처리</li>
                <li>• 현장 일정 협업</li>
              </ul>
            </div>
          </div>

          <div className="mt-8 rounded-[1.75rem] border border-yellow-400/20 bg-yellow-400/5 p-6">
            <div className="text-lg font-bold">부동산 협업 안내</div>
            <p className="mt-2 text-sm text-neutral-300 leading-6">
              부동산 중개사분들이 철거 또는 원상복구 현장을 연결해 주시면
              빠른 견적 상담과 일정 협의를 통해 작업 진행이 가능합니다.
              서울 · 경기 전지역 현장 대응 가능합니다.
            </p>
          </div>

          <div className="mt-10 rounded-[2rem] border border-yellow-400/20 bg-yellow-400/5 p-8 text-center">
            <h3 className="text-2xl font-black">협업 문의</h3>
            <p className="mt-3 text-neutral-300">
              부동산 중개사 · 인테리어 업체 협업 문의 환영합니다.
            </p>

            <div className="mt-6 flex flex-wrap justify-center gap-4">
              <a href={`tel:${phone}`} className="rounded-xl bg-yellow-400 px-6 py-3 font-black text-black">
                전화 문의
              </a>
              <a href={kakao} className="rounded-xl border border-yellow-400 px-6 py-3 font-black text-yellow-300">
                카카오톡 문의
              </a>
            </div>
          </div>
        </div>
      </section>

      <section className="border-t border-white/10 bg-neutral-950/70">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="grid gap-6 lg:grid-cols-[1.2fr_1fr]">
            <div className="rounded-[2rem] border border-white/10 bg-white/5 p-8">
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Real Estate Partners</p>
              <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">부동산 중개사 전용 협업 안내</h2>
              <p className="mt-4 text-neutral-300 leading-7">
                빠루꼬 철거는 상가 임대 종료, 원상복구, 공실 정리, 매장 인수 전 철거가 필요한 현장에 빠르게 대응합니다.
                부동산 중개사분들이 현장을 연결해 주시면 사진 상담부터 견적, 일정 협의까지 신속하게 진행합니다.
              </p>
              <div className="mt-6 grid gap-3 sm:grid-cols-2">
                {[
                  "상가 원상복구 현장 협업",
                  "공실 정리 및 내부 철거",
                  "임대 종료 철거 상담",
                  "서울 · 경기 전지역 대응",
                ].map((item) => (
                  <div key={item} className="rounded-2xl border border-yellow-400/20 bg-yellow-400/5 px-4 py-3 text-sm text-neutral-200">
                    {item}
                  </div>
                ))}
              </div>
              <div className="mt-6 flex flex-wrap gap-3">
                <a href={`tel:${phone}`} className="rounded-2xl bg-yellow-400 px-5 py-3 text-sm font-black text-black">
                  중개사 협업 전화
                </a>
                <a href={kakao} className="rounded-2xl border border-yellow-400/30 bg-yellow-400/10 px-5 py-3 text-sm font-black text-yellow-300">
                  카카오톡 협업 문의
                </a>
              </div>
            </div>

            <div className="rounded-[2rem] border border-yellow-400/20 bg-yellow-400/5 p-8">
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">SEO</p>
              <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">서울 · 경기 철거 키워드</h2>
              <p className="mt-4 text-neutral-300 leading-7">
                빠루꼬 철거는 서울 철거, 경기 철거, 상가 철거, 사무실 철거, 원상복구, 폐기물 처리 문의를 받고 있습니다.
                홈페이지와 네이버 플레이스, 블로그, 인스타그램을 함께 운영하면 검색 노출과 문의 전환에 도움이 됩니다.
              </p>
              <div className="mt-6 flex flex-wrap gap-2">
                {seoRegions.map((item) => (
                  <span key={item} className="rounded-full border border-white/10 bg-black/20 px-3 py-2 text-xs font-bold text-yellow-300">
                    {item}
                  </span>
                ))}
              </div>
            </div>
          </div>
        </div>
      </section>

      <section className="border-t border-white/10 bg-neutral-950/70">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="mb-10 max-w-2xl">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Gallery</p>
            <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">작업사진 갤러리</h2>
            <p className="mt-3 text-neutral-400">
              아래 영역에 실제 현장 사진을 넣으면 홈페이지 완성도가 훨씬 올라갑니다.
            </p>
          </div>
          <div className="grid gap-4 sm:grid-cols-2 lg:grid-cols-3">
            {gallery.map((item, idx) => (
              <div key={item} className="group relative overflow-hidden rounded-[1.75rem] border border-white/10 bg-neutral-900 min-h-[220px] p-5">
                <div className="absolute inset-0 bg-gradient-to-br from-yellow-500/10 via-transparent to-orange-500/10 group-hover:scale-105 transition" />
                <div className="relative flex h-full flex-col justify-between">
                  <div className="inline-flex w-fit rounded-xl bg-black/40 px-3 py-1 text-xs font-bold text-yellow-300">PHOTO {idx + 1}</div>
                  <div>
                    <div className="text-xl font-bold">{item}</div>
                    <p className="mt-2 text-sm text-neutral-400">실제 사진으로 교체해서 사용하세요.</p>
                  </div>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      <section className="border-t border-white/10 bg-neutral-900/50">
        <div className="mx-auto max-w-7xl px-6 py-16 lg:px-10 lg:py-20">
          <div className="grid gap-6 lg:grid-cols-2">
            <div className="rounded-[2rem] border border-white/10 bg-white/5 p-8">
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Before & After</p>
              <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">철거 전후 비교</h2>
              <p className="mt-4 text-neutral-400">
                실제 현장에서는 전후 사진을 나란히 넣으면 가장 신뢰도가 높습니다.
              </p>
              <div className="mt-6 grid grid-cols-2 gap-4">
                <div className="rounded-[1.5rem] border border-white/10 bg-neutral-950 p-5 min-h-[220px]">
                  <div className="text-sm font-bold text-yellow-300">BEFORE</div>
                  <div className="mt-3 text-xl font-bold">철거 전</div>
                  <p className="mt-2 text-sm text-neutral-400">기존 매장 / 사무실 / 주택 내부 사진</p>
                </div>
                <div className="rounded-[1.5rem] border border-white/10 bg-neutral-950 p-5 min-h-[220px]">
                  <div className="text-sm font-bold text-yellow-300">AFTER</div>
                  <div className="mt-3 text-xl font-bold">철거 후</div>
                  <p className="mt-2 text-sm text-neutral-400">철거 완료 또는 원상복구 완료 사진</p>
                </div>
              </div>
            </div>

            <div className="rounded-[2rem] border border-yellow-400/20 bg-yellow-400/5 p-8">
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-yellow-400">Location</p>
              <h2 className="mt-3 text-3xl font-black tracking-tight sm:text-4xl">오시는 길</h2>
              <p className="mt-4 text-neutral-300">
                경기도 시흥시 정왕동 375-1
              </p>
              <div className="mt-6 rounded-[1.5rem] border border-white/10 bg-neutral-950 p-6 min-h-[220px] flex items-center justify-center text-center text-neutral-400">
                네이버지도 / 카카오맵 iframe 또는 지도 이미지 영역
              </div>
              <p className="mt-4 text-sm text-neutral-400">
                실제 배포 시 네이버지도 링크나 카카오맵 링크를 연결하면 됩니다.
              </p>
            </div>
          </div>
        </div>
      </section>

      <footer className="border-t border-white/10 bg-black/30">
        <div className="mx-auto flex max-w-7xl flex-col gap-3 px-6 py-8 text-sm text-neutral-400 lg:px-10">
          <div className="text-lg font-black text-white">빠루꼬 철거</div>
          <div>상가 · 사무실 · 주택 철거 전문 / 원상복구 / 부분철거 / 폐기물 처리</div>
          <div>작업 지역: 서울 · 경기 전지역</div>
          <div>대표자: 김호종</div>
          <div>사업자등록번호: 579-43-01220</div>
          <div>주소: 경기도 시흥시 정왕동 375-1</div>
          <div>이메일: pparukko@naver.com</div>
          <div className="flex flex-wrap gap-4 pt-2">
            <a href={`tel:${phone}`} className="hover:text-white">전화 상담</a>
            <a href={kakao} className="hover:text-white">카카오톡 상담</a>
            <a href={instagram} className="hover:text-white">인스타그램</a>
          </div>
        </div>
      </footer>

      {/* 모바일 하단 고정 상담 버튼 */}
      <div className="fixed bottom-0 left-0 right-0 z-50 flex md:hidden">
        <a
          href={`tel:${phone}`}
          className="flex-1 bg-yellow-400 py-4 text-center font-black text-black"
        >
          전화 상담
        </a>
        <a
          href={kakao}
          className="flex-1 bg-neutral-900 py-4 text-center font-black text-white border-l border-neutral-700"
        >
          카카오톡 상담
        </a>
      </div>
    </div>
  );
}
