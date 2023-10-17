# sau khi merge request tu release sang main

- Tai main o local: se pull code ve de action them `git pull`
- tao tag cho phien ban product o main `git tag 'v1.0.0'`
- sau do day tag len `git push --tags`
- sau khi trien khai len `main` xong can xoa nhanh `release` moi trien khai xong:
  - tai local `git branch -d release-1.0.0` (tren github van con nhe :D)
  - xoa branch tai github `git push origin -d release-1.0.0`
  - xoa branch `feature` tai local va github:
    - `git push origin -d feature/1-add-test-model-file`
    - `git branch -d feature/1-add-test-model-file`; neu chua merge het se can su dung cau lenh `git branch -D feature/1-add-test-model-file` de xoa;
-
