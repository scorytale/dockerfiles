FROM scorytale/elixir

RUN apk add --no-cache --update \
      nodejs nodejs-npm \
      imagemagick

RUN mix archive.install https://github.com/phoenixframework/archives/raw/master/phx_new.ez --force

EXPOSE 4000

CMD ["mix", "phoenix.server"]

