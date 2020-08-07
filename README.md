# TIL



**20.08.06**

- git repository에서 폴더/파일 삭제하기 : local에서는 그대로 두고 원격 저장소에서만 지우기
```bash
git rm -r -cached <폴더 및 파일명>
git commit -m ""
git push origin master
```


**20.08.07**

- mysql DB 생성 및 aws 서버 연결❗

- mysql로 생성한 DB를 django models.py에 생성
```python
python manage.py inspectdb
```

- models.py에서 변경한 값을 DB에 적용
```python
python manage.py migrate
```
