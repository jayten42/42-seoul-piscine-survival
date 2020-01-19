# CLI (Command Line Interface)
- 명령 줄 인터페이스
- 42 에서는 Mac에서 터미널을 사용하는 환경이다. 때문에 기본적인 Command(명령어)를 알면 좋다.
- 터미널은 Windows의 CMD 창을 생각하면 된다.

> 명령어는 Full Name 을 기억하면 이해하기 편하고 외우기 쉽다.

### pwd

- Print Working Directory
- 현재 작업중인 디렉토리 경로를 출력한다.

### echo

- 매아리
- `echo "message"` message를 출력한다

### man

- manual
- `man command`command (명령어) 의 메뉴얼을 볼수 있다.
- RTFM : Read The Fucking Manual

### cd

- Change Directory
- `cd 경로` 형태로 사용하며, 경로로 이동한다.
- 이때, 상대경로, 절대 경로를 사용할 수 있다.
- `.` 현재 디렉토리
- `..` 상위 디렉토리
- `cd ..` 상위 디렉토리로 이동

### ls

- list
- 파일 목록을 보여준다.
- `list 경로(혹은 파일)` 경로내의 파일과 디렉토리를 보여준다.

### mkdir

- Make Directory
- 새로운 디렉토리를 생성한다.
- `mkdir newDir` newDir 이라는 이름의 디렉토리를 생성한다.

### touch

- 진짜 그냥 손으로 만진다는 뉘앙스 같다.
- `touch 파일` 로 사용된다.
- 기존에 없는 파일일 경우, 새로 생성
- 기존에 있는 파일일 경우, 수정 날짜 변경

### cp

- Copy
- 파일이나 디렉토리를 복사한다.
- `cp 파일(혹은 디렉토리) 복사할위치`
- `cp file1 ../` file1을 상위 디렉토리로 복사한다
- `cp file1 file2` file1을 현재디렉토리에 file2로 복사한다.
- 이 때에도 상대경로, 절대경로를 사용 가능하다

### mv

- Move
- 파일이나 디렉토리를 이동한다.
- 경우에 따라 이름을 변경하는 용도로도 사용된다.
- `mv 파일(혹은 디렉토리) 옮길위치`
- `mv file1 ../` file1을 상위 디렉토리로 이동한다.
- `mv file1 file2` file1의 이름을 file2로 변경한다.
- 이 때에도 상대경로, 절대경로를 사용 가능하다

### rm

- Remove
- 파일이나 디렉토리를 삭제한다.
- `rm 파일` 파일을 삭제한다.
- 이 때에도 상대경로, 절대경로를 사용 가능하다

### rmdir

- Remove Directory
- 디렉토리를 삭제한다.
- `rm 디렉토리` 디렉토리를 삭제한다.
- 이 때에도 상대경로, 절대경로를 사용 가능하다

### cat

- Concantenate file and print
- 본래 용도는 여러 파일 내용을 합쳐서 한번에 출력한다.
- 하지만 한개의 파일을 대상으로 주로 사용한다.
- `cat a.txt` a.txt 파일의 내용을 출력한다.

### ln

- link
- 윈도우에서 우리가 흔히 아는 바로가기를 생각하면 된다.
- Symbolic link 와 hard link로 나뉘는데 (다시 확실한 공부 필요)

### grep
- Global Regular Expression Print.
- 패턴이 매칭된 모든 줄을 출력.
- `grep [options] PATTERN [FILE...]`
