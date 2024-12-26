### 1. KMS 특징이 아닌 것은?
1. AWS를 사용하기 위해서는 반드시 IAM 인증을 거쳐야 한다.
2. CloudTrail을 통해 모든 API 호출을 검사할 수 있다.
3. 기밀 정보는 일반 텍스트에 담아내서는 안된다.
4. KMS 키 유형에는 Symmetric과 Asymmetric이 있는데, 두 차이는 키의 개수이다.

### 2.전송중 암호화를 하는 이유는?
서술

### 3. CloudWatch Logs에 저장된 기존 로그를 암호화하는 방법은?
1. create-log-group API 호출
2. update-log-group API 호출
3. CloudWatch Logs 콘솔에서 암호화
4. Associate-kms-key API 호출

### 4. S3 버킷에 저장된 객체에 SSL 요청을 적용할 수 있는 IAM 조건은?
1. aws:EnforceSSL
2. s3:SecureTransport
3. aws:SecureTransport
4. s3:EnforceSSL
