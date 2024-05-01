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
  - [libft-unit-test](https://github.com/alelievr/libft-unit-test)
    ```sh
    git submodule update --remote --init libft-unit-test
    cd libft-unit-test
    make
    ```

    Makefileに適切なパスを設定する

    ```diff
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
