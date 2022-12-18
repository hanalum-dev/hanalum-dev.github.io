## Dev

> gem install bundler

> bundle install

> bundle exec jekyll serve --watch

- 주의사항
  - _config.yml 파일 수정시에는 `bundle exec jekyll serve --watch` 명령어를 종료하고 실행해야 반영된다.

## Docs

[template docs](https://bootstrapstarter.com/jekyll-theme-memoirs/)

## 2022.12.18
ruby버전과 특정 gem(nokogiri) 버전 호환성 문제 발생 시 해결방법

> bundle update nokogiri

> bundle install

> jekyll serve
만약 오류나면
> bundle exec jekyll serve