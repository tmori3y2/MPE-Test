---
markdown:
  image_dir: /assets
  absolute_image_path: true
---

# Test Pattern

> @import "test_001.puml"

> \!\[](/assets\\test_001.png?0.975359158084361)

![](/assets\test_001.png?0.975359158084361)

# Test condition 1

* Project Path (Open Folder): "D:\\Projects\\MPE-Test\\assets_test"

* Open test_001.md

* Save as markdown

* Open test_001_.md

* Change .png file name into test_001.png.

* check img/@src by Developer Tools and describe it.

* Change output .md file name into test_001_results.md.

src:

file:///D:\\Projects\\MPE-Test\\assets_test\\
assets\\test_001.png?0.975359158084361

# Test condotion 2

* Project Path (Open Folder): "D:\\Projects\\MPE-Test"

* Open test_001_results.md.

* check img/@src by Developer Tools and describe it.

* Save test_001_results.md.

src: (invalid path)

file:///D:\\Projects\\MPE-Test\\assets\\test_001.png?0.975359158084361

# Test condotion 3

* Project Path (Open Folder): "D:\\Projects\\MPE-Test\\assets_test\\test1"

* Open test_001_results.md.

* check img/@src by Developer Tools and describe it.

* Save test_001_results.md.

src: (invalid path)

file:///D:\\Projects\\MPE-Test\\assets_test\\test1\\assets\\test_001.png?0.975359158084361
