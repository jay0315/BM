# BM  my first build
i love coffee,baskteball

def add(x):
    return x + 2;


class TestClass(object):
    # 测试是否相等
    def test_add(self):
        assert add(2) == 5

    # 测试包含
    def test_in(self):
        a = 'hello world'
        b = 'he'
        assert b in a

    # 测试不包含
    def test_not_in(self):
        a = 'Hello'
        b = 'hi'
        assert b not in a
