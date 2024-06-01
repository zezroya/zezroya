# 오픈소스SW 과제2 README파일 작성하기

- 👋 Hi, I’m @zezroya
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

| 오픈소스SW 과제2 README파일 작성하기 |
|--------------------------------------|
| top, ps, jobs, kill 명령어 조사하기  |
| 다양한 Markdown 기능을 활용해보기    |
| 조사한내용을 README파일에 저장!      |

# 오픈소스SW 과제2 README파일 작성하기

## 리눅스 명령어 조사: top, ps, jobs, kill

| 명령어 | 설명                                          | 사용법                   | 주요 옵션                            | 예제                          |
|--------|---------------------------------------------|--------------------------|-------------------------------------|-------------------------------|
| `top`  | 실시간으로 프로세스를 모니터링               | `top`                    | `-d` (갱신 주기), `-p` (특정 PID)   | `top -d 2`                    |
| `ps`   | 현재 실행 중인 프로세스를 표시               | `ps`                     | `aux` (상세 정보), `-e` (모든 프로세스) | `ps aux`, `ps -e`             |
| `jobs` | 현재 셸 세션의 백그라운드 작업 상태 표시     | `jobs`                   | `-l` (상세 정보), `-n` (마지막 작업) | `jobs -l`                     |
| `kill` | 특정 프로세스를 종료                         | `kill [signal] PID`      | `-9` (즉시 종료), `-15` (정상 종료) | `kill -9 1234`, `kill -l`     |

## 명령어 상세 설명

### 1. top 명령어

#### 설명
`top` 명령어는 시스템의 모든 실행 중인 프로세스를 실시간으로 모니터링하는 데 사용됩니다. CPU 사용률, 메모리 사용량, 실행 중인 프로세스의 상태 등을 실시간으로 확인할 수 있습니다.

#### 사용법
```bash
top



![bird](https://github.com/zezroya/zezroya/blob/main/1.jpg)

