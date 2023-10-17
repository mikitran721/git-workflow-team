# git-workflow-team

Miki Tran thu nghiem Merge Github, su dung TAG, ISSUE

- VD Team 10 users;

# LUU Y:

- nhanh main la nhanh deploy chua source code chinh & chuan

## BUOC THUC HIEN: NHANH `FEATURE` doi voi DEV

- B1: day file len github; tao branch chinh `main`
- B2: `git branch develop` tao them nhanh cho muc dich dev

  - su dung `git branch` de kiem tra danh sach cac branch hien co
  - su dung `git checkout develop` de chuyen qua nhanh `develop`

- B3: Tao Issues: danh cho quan ly nhom
  - `issue` la cac tasks duoc giao cho dev thuc hien:
  - Tao label cho task sap giao viec;
  - tao issue gan cho member & gan label phu hop
  - khi dev commit code len can vao dung vi tri #number label voi task duoc giao; vd: `Miki - create test.model.js file #1` co trong ISSUE LIST.
- B4: nguoi duoc giao viec:

  - thuc hien chuyen vung lam viec vao nhanh `develop` voi cau lenh `git push -u origin develop`
  - tao branch dev cho task moi voi name co so cung voi #tag.number duoc giao;
    - vd: `git checkout -b feature/1-add-test-model-file develop`; trong do `feature/1` la ten cua label/#number lien quan toi issue duoc giao
  - code cac file theo issue duoc giao
  - add file lien quan toi task
  - commit theo cu phap:
    - `GIT COMMIT -M '#1 - MIKI UPDATE TEST MODEL'` ; voi #1 la so tag cua issue;
    - sau do push theo lenh ``- neu quen co the go`git push` se duoc goi y

- B5: khi xac dinh dung #issue da upate dung; leader se tien hanh `refer -review code` code tu nhanh feature sang nhanh develop;

  - khi comment t.bao nho them #tagnumber vao vung commet de biet da `merge/refer` Issue nao. -- thao tac `tao pull request`

- B6: team lead se `CONFIRM MERGE` & DE LAI COMMENT

## BUOC THUC HIEN VOI `TEAMLEAD` nhanh trung gian `develop`
