---
markdown:
  image_dir: assets
  absolute_image_path: true
---

# Test Pattern

> @import "test_003.puml"

> \!\[](/test3\assets\test_003.png?0.249173070619799)

![](/test3\assets\test_003.png?0.249173070619799)

# Test condition 1

* Project Path (Open Folder): "D:\\Projects\\MPE-Test\\assets_test"

* Open test_003.md

* Save as markdown

* Open test_003_.md

* Change .png file name into test_003.png.

* check img/@src by Developer Tools and describe it.

* Change output .md file name into test_003_results.md.

src:

file:///D:\\Projects\\MPE-Test\\assets_test\\test3\\assets\\test_003.png?0.249173070619799

# Test condotion 2

* Project Path (Open Folder): "D:\\Projects\\MPE-Test"

* Open test_003_results.md.

* check img/@src by Developer Tools and describe it.

* Save test_003_results.md.

src: (invalid path)

file:///D:\\Projects\\MPE-Test\\test3\\assets\\test_003.png?0.249173070619799

# Test condotion 3

* Project Path (Open Folder): "D:\\Projects\\MPE-Test\\assets_test\\test1"

* Open test_003_results.md.

* check img/@src by Developer Tools and describe it.

* Save test_003_results.md.

src: (invalid path)

file:///D:\\Projects\\MPE-Test\\assets_test\\test3\\test3\\assets\\test_003.png?0.249173070619799
