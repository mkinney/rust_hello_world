# using https://doc.rust-lang.org/1.0.0/book/hello-cargo.html
cargo new hello_world --bin
docker build -t myrust/hello .
docker run -it --rm myrust/hello
