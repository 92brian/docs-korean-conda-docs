개요
========

.. contents::

콘다를 사용하는 가장 빠른 방법은 :doc:`/install/quick_ko` 가이드를 보고 시작하는 것이다. 콘다의 사용자 가이드 중 가장 짧은 :doc:`콘다 테스트 드라이브 </test-drive_ko>` 를 따라 진행되고 30분 정도 소요된다.

이제 환경, 파이썬, 그 외 다른 패키지 관리에 대한 자세한 설명을 보자.

각각의 커맨드에 대한 완전한 사용법은 :doc:`/commands_ko` 가이드를 보자. 터미널창에서 커맨드 뒤에 ``--help`` 플래그를 입력해도 동일한 가이드를 볼 수 있다.

서론
~~~~~~~~~~~~~

패키지 관리자가 패지지를 검색하고 설치하는 것을 도와준다는건 이미 알 것이다. 다른 버전의 파이썬을 요구하는 패키지가 필요할 때 다른 환경 관리자로 전환하지 않아도 된다. 콘다는 패키지 관리자이면서 환경 관리자이기 때문이다. 몇 줄의 커맨드로 다른 파이썬 버전을 사용하는 환경을 설정함과 동시에 기존 파이썬 버전을 사용하던 환경을 계속 사용할 수 있다.

커맨드에 대한 완전한 문서가 필요하다면 커맨드 뒤에 ``--help`` 를 붙이면 된다. 예를 들어 conda update 커맨드에 대해 알고 싶다면:

.. code::

     conda update --help

동일한 도움말을 온라인에서도 볼 수 있다. :doc:`/commands_ko`.

콘다 관리
~~~~~~~~~~~~~~~

주의: 리눅스, OS X, 윈도우 커맨드 프롬프트 중 어떤 것을 사용하던 간에 터미널창에서 사용하는 콘다 커맨드는 몇몇 예외를 제외하고 동일하다.

콘다가 설치 여부와 버전 확인
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

알맞은 환경에서 시작하는지 확인하기 위해 아나콘다가 제대로 설치 되었는지 확인하자. 터미널창에서 다음 커맨드를 입력한다.:

.. code::

   conda --version

``conda 3.11.0`` 과 같이 콘다는 설치된 버전을 보여줄 것이다.

주의: 에러 메시지가 나타나면 아나콘다 또는 미니콘다가 설치된 사용자 계정에 로그인 했는지 확인한다. 아나콘다 또는 미니콘다를 찾을 수 있는 디렉토리에 있는지와 아나콘다 또는 미니콘다의 설치 이후에 터미널창을 다시 열었는지 확인한다.

현재 버전으로 콘다 업데이트
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

다음은 conda update 커맨드로 콘다를 업데이트 하자.:

.. code::

   conda update conda

콘다는 버전을 비교하고 설치가능한 버전이 무엇인지 알려줄 것이다. 그 외에도 콘다 업데이트 과정에서 자동으로 업데이트 되거나 변경되는 패키지를 알려줄 것이다. 새로운 버전의 콘다가 존재하면 Y 를 눌러 업데이트한다.:

.. code::

   Proceed ([y]/n)? y

다음은 :doc:`envs_ko` 를 보자.
