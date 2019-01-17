FROM openjdk:8-alpine as builder
WORKDIR /build
COPY Sample8.java .
RUN javac ./Sample8.java

FROM openjdk:8-jre-alpine
WORKDIR /app
COPY --from=builder /build .
CMD java Sample8
