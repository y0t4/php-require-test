php-require-test
================
require の動作テスト

まずは普通にindex.phpにアクセスする。
その後に、./required.php を ./required.php.back などに変更してみる。
index.phpの挙動が変わっている。

require は、親ディレクトリに対象のファイルがある場合にはそちらを優先するっぽい。
