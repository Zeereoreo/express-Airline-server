# fe-sprint-statesairline-server 
morgan	HTTP 요청 로그를 남깁니다.
var morgan = require('morgan')
morgan('tiny')

미들웨어 종류

body-parser	HTTP 요청 body를 파싱합니다. body, co-body, 그리고 raw-body도 참고하세요.	express.bodyParser
compression	HTTP 요청들을 압축합니다.	express.compress
connect-rid	고유한 요청 ID를 생성합니다.	없음
cookie-parser	쿠키 헤더를 파싱하고 req.cookies에 할당합니다. cookies와 keygrip도 참고하세요.	express.cookieParser
cookie-session	쿠키 기반의 세션을 만듭니다.	express.cookieSession
cors	다양한 옵션들을 이용하여 Cross-origin resource sharing (CORS)를 활성화합니다.	없음
errorhandler	개발 중에 발생하는 에러를 핸들링하고 디버깅합니다.	express.errorHandler
method-override	헤더를 이용해 HTTP method를 덮어씁니다.	express.methodOverride
morgan	HTTP 요청 로그를 남깁니다.	express.logger
multer	multi-part 폼 데이터를 처리합니다.	express.bodyParser
response-time	응답 시간을 기록합니다.	express.responseTime
serve-favicon	파비콘을 제공합니다.	express.favicon
serve-index	주어진 경로의 디렉토리 리스트를 제공합니다.	express.directory
serve-static	정적 파일을 제공합니다.	express.static
session	서버 기반의 세션을 만듭니다 (개발 전용).	express.session
timeout	HTTP 요청 처리를 위해 timeout을 만듭니다.	express.timeout
vhost	가상 도메인을 만듭니다.	express.vhost
