# using https://doc.rust-lang.org/1.0.0/book/hello-cargo.html

# created project
cargo new hello_world --bin

# build
cargo build

# run
cargo run

# build docker container
docker build -t myrust/hello .

# ensure docker container with just app works
docker run -it --rm myrust/hello
