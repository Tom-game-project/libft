# libft

## テストの方法

- 自作テスト

  test.c

- 公開されているテスト

  - [libftTester](https://github.com/Tripouille/libftTester)
    ```sh
    git submodule update --remote --init libftTester
    ``` 

    ```sh
    cd libftTester
    make
    ```

    Makefileで`git pull`が使用されているのでremoteの設定を変更する必要がある

    ```patch
    update:
    - @git pull
    + @git pull origin heads/master
    ```

  - [libft-unit-test](https://github.com/alelievr/libft-unit-test)
    ```sh
    git submodule update --remote --init libft-unit-test
    cd libft-unit-test
    make
    ```

    Makefileに適切なパスを設定する

    ```patch
    - LIBFTDIR	=	../libft
    + LIBFTDIR	=	../
    ```

  - [libft-tester-tokyo](https://github.com/usatie/libft-tester-tokyo)
    ```sh
    git submodule update --remote --init libft-tester-tokyo
    cd libft-tester-tokyo
    make
    make bonus
    ```
