# Physics 1: Interactive Demos
**경상국립대학교 수학물리학부 1학년 물리학1 교과목 보조자료**

Landing page for the interactive web demos that accompany *Physics 1* (물리학1), a first-year course in the School of Mathematics and Physics, Gyeongsang National University. Every demo comes in both English and Korean.

경상국립대학교 수학물리학부 1학년 과목인 물리학1의 인터랙티브 웹 데모 모음입니다. 모든 데모는 영어판과 한국어판이 함께 있습니다.

**Live page:** https://lshlj82.github.io/physics1-GNU/

**Repository:** https://github.com/lshlj82/physics1-GNU

Created by Claude Opus 5.5, based on the lecture notes by Prof. Sang Hoon Lee.
이상훈 교수의 강의노트를 바탕으로 Claude Opus 5.5가 만들었습니다.

## Demos · 데모 목록

| # | Demo | 데모 | Links |
|---|------|------|-------|
| 1 | Describing motion | 운동의 기술 | [English](https://lshlj82.github.io/motion-description/motion-en.html) · [한국어](https://lshlj82.github.io/motion-description/motion-ko.html) · [source](https://github.com/lshlj82/motion-description) |
| 2 | Newton's laws of motion | 뉴턴의 운동법칙 | [English](https://lshlj82.github.io/Newton-laws-of-motion/newton-en.html) · [한국어](https://lshlj82.github.io/Newton-laws-of-motion/newton-ko.html) · [source](https://github.com/lshlj82/Newton-laws-of-motion) |
| 3 | Work and energy | 일과 에너지 | [English](https://lshlj82.github.io/work-energy/energy-en.html) · [한국어](https://lshlj82.github.io/work-energy/energy-ko.html) · [source](https://github.com/lshlj82/work-energy) |
| 4 | Linear momentum | 선운동량 | [English](https://lshlj82.github.io/linear-momentum/momentum-en.html) · [한국어](https://lshlj82.github.io/linear-momentum/momentum-ko.html) · [source](https://github.com/lshlj82/linear-momentum) |
| 5 | Rotational motion | 회전운동 | [English](https://lshlj82.github.io/rotational-motion/rotation-en.html) · [한국어](https://lshlj82.github.io/rotational-motion/rotation-ko.html) · [source](https://github.com/lshlj82/rotational-motion) |
| 6 | Oscillation and wave | 진동과 파동 | [English](https://lshlj82.github.io/oscillation-wave/oscillation-wave-en.html) · [한국어](https://lshlj82.github.io/oscillation-wave/oscillation-wave-ko.html) · [source](https://github.com/lshlj82/oscillation-wave) |
| 7 | Thermodynamics: the 1st law | 열역학: 제 1법칙 | [English](https://lshlj82.github.io/thermodynamics-1st/thermo1-en.html) · [한국어](https://lshlj82.github.io/thermodynamics-1st/thermo1-ko.html) · [source](https://github.com/lshlj82/thermodynamics-1st) |
| 8 | Thermodynamics: the 2nd law | 열역학: 제 2법칙 | [English](https://lshlj82.github.io/thermodynamics-2nd/thermo2-en.html) · [한국어](https://lshlj82.github.io/thermodynamics-2nd/thermo2-ko.html) · [source](https://github.com/lshlj82/thermodynamics-2nd) |

## About the page · 페이지 소개

The page is a single self-contained `index.html` with no build step. Its header replays the rocket from demo 4: a rocket with an initial mass of 50 t, 80% of it fuel, burns fuel at 500 kg/s with an exhaust speed of 3000 m/s relative to the rocket. As it throws fuel out the back, the stars stream past faster, and a plot follows the speed gained, Δ*v* = *v*<sub>rel</sub> ln(*M*<sub>i</sub>/*M*), up to *v*<sub>rel</sub> ln 5 ≈ 4.8 km/s. The 80-second burn plays in 6 seconds, followed by a short coast, and then repeats.

The page supports light and dark mode and adapts to phone screens. For visitors who have reduced motion turned on, it shows a still frame instead of the animation.

페이지는 빌드 과정 없이 `index.html` 파일 하나로 이루어져 있습니다. 상단에서는 데모 4의 로켓을 다시 보여줍니다. 처음 질량 50 t 가운데 80%가 연료인 로켓이 로켓에 대한 배기 속력 3000 m/s로 연료를 초당 500 kg씩 내뿜습니다. 연료를 뒤로 내뿜을수록 별이 더 빨리 지나가고, 그래프는 얻은 속력 Δ*v* = *v*<sub>rel</sub> ln(*M*<sub>i</sub>/*M*)이 *v*<sub>rel</sub> ln 5 ≈ 4.8 km/s까지 커지는 모습을 보여줍니다. 80초 동안의 연소를 6초로 줄여 보여 주고, 잠시 관성으로 날아간 뒤 다시 반복합니다.

## Running locally · 로컬에서 실행

Open `index.html` in any modern browser. Fonts load from Google Fonts when online and fall back to system fonts otherwise.

## Deploying · 배포

1. Put `index.html` and this `README.md` at the root of the repository.
2. In **Settings → Pages**, set the source to the `main` branch, root folder.
3. The page will be served at `https://lshlj82.github.io/<repository-name>/`.

## References · 참고문헌

- Prof. Sang Hoon Lee, lecture notes for Physics 1. (이상훈 교수, 물리학1 강의노트)
