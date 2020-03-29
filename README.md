# Practice rust book

## Abstract

Practice rust book for Japanease.

https://doc.rust-jp.rs/

## Create project

1. Add new project

        cargo new --vcs none --bin new_project_name

2. Add workspace members for Cargo.toml

        members = [
            ...,
            "new_project_name",
        ]
