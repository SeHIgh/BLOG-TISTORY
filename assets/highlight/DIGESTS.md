## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/highlight.min.js"
  integrity="sha384-pGqTJHE/m20W4oDrfxTVzOutpMhjK3uP/0lReY0Jq/KInpuJSXUnk4WAYbciCLqT"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/languages/go.min.js"
  integrity="sha384-Mtb4EH3R9NMDME1sPQALOYR8KGqwrXAtmc6XGxDd0XaXB23irPKsuET0JjZt5utI"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-no5/zgQGupzPFGWV8VpJzfQau5/GI2v5b7I45l6nKc8gMOxzBHfgyxNdjQEnmW94 /es/languages/bash.js
sha384-u2nRnIxVxHkjnpxFScw/XgxNVuLz4dXXiT56xbp+Kk2b8AuStNgggHNpM9HO569A /es/languages/bash.min.js
sha384-qimhSkVWof5rfaFajQk8KAtzSRYyIArcJCMKWdDcNq34F4uplk08wmEyUiYLmO+3 /es/languages/c.js
sha384-5fESKgrRcGs7I/89bn7NKFcHyvIVcmQIG4JfCEAV5Rg5VVtskrmGkHVOIsD1642v /es/languages/c.min.js
sha384-eM9Op3b0ilZ/iW7jeVAMo//MKcEXHCbg1Vf8SMrqds5LIOeF9+3qaX//TsnbItae /es/languages/cpp.js
sha384-+tDHTmLKfBxXgVksRhLEJM4z9PfcGQ2XsrZMDcdJ1SIlPZrtAR4+m4XUX+zJf5nf /es/languages/cpp.min.js
sha384-+9dzNYaLHp3OPspFCOJGrEwfiOV3yqeD/atUDYVt9zKUJ8IW2QxffCT2LfmGfwfW /es/languages/css.js
sha384-G44u1/pUATC8754FIKYqkCxCl9AQYnspnFxzuR3RB1YVnTvqOEofqvZNQMUWcY/1 /es/languages/css.min.js
sha384-XkaMmz1IWxxotnRaq8UyqY+r1C0SADoKTIT/8J84nio8ZUVtw9Xw2K+fBBvQ8ziT /es/languages/dart.js
sha384-XQur/dNXGWVSWOuMk+TsDoXfe5GzflLu972jJ72dqRV4N65jOT+h4GGpXQDstHWC /es/languages/dart.min.js
sha384-ZCfS+s/zxY7O2bm2KoVJo1wUrLEpJDHZAi/LJAdJF5XjnfSWICkg6wHd2SEJGpyR /es/languages/java.js
sha384-716dHwZ7zbZcnEwTe7DLxlm5tH3Iyl8vSW5a2kYPgusEdp5k3A3jeZt0Ck+CjYE0 /es/languages/java.min.js
sha384-oQpcUGMBf+VDTHOLQ1uhPp1FgNBo0OZc9gbXGuVFwAogHlkh/Iw6cvKKgcgCQkmV /es/languages/javascript.js
sha384-3T8DJ91yCa1//uY9h8Bo4QLrgEtbz4ILN2x9kSM4QWX9/1kKu6UXC3RAbVQV85UQ /es/languages/javascript.min.js
sha384-R87hRh4kF8+iz2sB6FvLrfR0XZBohjFXeJKIXld1Eji2UVi+M2+OIgJKma/9Ko6u /es/languages/json.js
sha384-QFDPNpqtrgZCuAr70TZJFM4VCY+xNnyGKwJw2EsWIBJOVcWAns9PHcLzecyDVv+x /es/languages/json.min.js
sha384-prYrGnTm7oh5PuKMqLmR+7SrkN+R30qFCvQLyWRjl7bJqveap4Mb3RDeCe84KHSC /es/languages/kotlin.js
sha384-yM8aIXHTDq77S7Ar7r/O8Ix2yH07cPC1z48Qh6HBzcG2+plE8YMQn9goknWvawaH /es/languages/kotlin.min.js
sha384-JkFMmKMbHcXjdfHauRnREGG6i73GyMisdqNivBm4Z9m2Oc82YIu5jQtIjLa508e8 /es/languages/markdown.js
sha384-65/lNNIY+ayhHTtFznjnyZ5w2NDdZIpSEcqjss/p4ex5JamZ46FdYwDDf6IBLCmE /es/languages/markdown.min.js
sha384-dkR9Qv3ZGmcTGGFP26gmcHC9DBgRYE0XLGxF3mBXlBZaBrscW0vIiVN7oTyQmrbe /es/languages/plaintext.js
sha384-AkqanemYxn6S3BQnW2++1+xqywaq2bJfFlfiAkPNd7Yv5t9YsS8tFzVVopyOa747 /es/languages/plaintext.min.js
sha384-8aLAoO/YSb+fhxwbMNNuUeq3x/FJJvtLwRq9nYpoyy4j85IpQURkoRySqJHBFlwu /es/languages/powershell.js
sha384-LA+GHsDHAleSQDZ+9MEiJmTnrJ392Nkux5b1RIiGmzAkRo+4dwKsjS0z/pzCXIFr /es/languages/powershell.min.js
sha384-e+d8RFZbtc5Pmt3xfX9uuElm63v5qOj7T5hAkkFbnYc1wEk7wCLlzOsm66MCf5Uk /es/languages/python.js
sha384-CPHh+9FxkWF3OtMZdTj5oQN1Qti0p4/5XBABz/JdgssOKHmfAOFz6Gu4tsG6MQiH /es/languages/python.min.js
sha384-NtjW7lI7c0f4eQUAsyYEvuUEeZPVwqBsisjGqqXls0p3Acc2wX2ppJxBvFC7jet4 /es/languages/r.js
sha384-+SoUnimzbx9Uf3b+zsNgb58sz3J3nRHE7ftjhuB8hvcb3K8D8G0Fe3Bu4lBrA3Fj /es/languages/r.min.js
sha384-kcAcxYNWYVMr2nwgsILhFHZH+OkRjbK6xazY53sIcW9bta3onTtDBKug0swjsiMC /es/languages/scss.js
sha384-mlx1v98SAsuX2QnqD9+dsXOfilvT7QQjfyOD3HTrvA4TXsxV4yjW/+TqhUADUuOH /es/languages/scss.min.js
sha384-VYwyP5ddOUunx1AGpbtE38OKY2PbjW9kk6X6622tvqprRJk6W8/tgMvI7MqaOZZw /es/languages/shell.js
sha384-gRgqaIgHrAR1qlo866rkV1AUahqopv0dnpFFLAC4X3jYTDagRCTxQBTMFGV1+x1U /es/languages/shell.min.js
sha384-ZX3mm6sjLYWMBTMUJYzvQXYHNWVJkD+t1ppx4BysyVs6cVhvYFVuwMlVCeAwtwm9 /es/languages/sql.js
sha384-DloKeCkj/pTPHeqWu3keGoEPpZJGm44yQjSmSfpWasykAMUobM0hcYFFPsg1PE6K /es/languages/sql.min.js
sha384-5tfPU5gS6J1PWMpLzFJzYt4O09dEwu0Ie9HPKYUQ43EE25lVsyugx9jVH0VViMor /es/languages/swift.js
sha384-a+qBlyBQMw6U8FrlXL2OodB7uR5S1diebujSfAM76WdYSl3ydnlxf8MCpGaiGgWG /es/languages/swift.min.js
sha384-BcyijKQAe0oJGoEBf0y/+dTJjKiy4bIAVdjreJw+MiOkPgCEjM/2FY2+W7K6tcEZ /es/languages/typescript.js
sha384-Mfjt0R07QBpLXhGWeCetLw7s2mTQSoXmcyYnfsSNq4V4YG3FwayBjxod9MxjSB1x /es/languages/typescript.min.js
sha384-4601pgEctPyGn7PKZTLv16bd6cWJLZrCg5a+/9ARj1cg9na6NwC+L767YLzdvSdk /es/languages/vim.js
sha384-iGCHxJTxvjzc4eyRff/+05+KaernFwSKiHceFSeDycK+vr6zh9ba2fMppsaMscuO /es/languages/vim.min.js
sha384-Tdx2DY9ZTHx3KhVXYqOVKx3q1zOboDGlTTv8sgMlER8y4WETtqL+C4VQ7B4A0OGq /es/languages/xml.js
sha384-n9ZezaAVj8pK1BIFZQxmC1BM9yGuBNRgvsOxHMHPCXzqYd1gSYIu9KjgGEm8K57w /es/languages/xml.min.js
sha384-40MP6/ECSjYaTAIf+/ibE2FPeFPQ53WbASndXxMOcXiQtgLbGXUStZVuPSngp7OD /es/languages/yaml.js
sha384-vXmhozexi2dHQBoniIEbWI5ZqDxyVfUs96BUGpqjWL1aberSp9pyxbvK8WCNASGB /es/languages/yaml.min.js
sha384-4SbTAv3AX2fuPCpSv6HW3p07YgA7hFfcwG2zJHtYv0ATIt1juD3IXj2NSYwTeIpm /languages/bash.js
sha384-83HvQQdGTWqnRLmgm19NjCb1+/awKJGytUX9sm3HJb2ddZ9Fs1Bst2bZogFjt9rr /languages/bash.min.js
sha384-WHdxyD51Y+ytDdcYGVkKHQOThUwwhLl/1GvZxHTHL4ImI4NS32L/B8bvB/1zN/Mk /languages/c.js
sha384-jtwnwOYA+K4zYN55fA4z4U0PTK5oEp4RcLYaXkYRKO3UUzge1o21ArmvKmTRdh/d /languages/c.min.js
sha384-M2wpTxQe2N0750xYZ0zTinwbmjsZjdtuS7twUUP2dxtHR0YqhY3JuUFyyhANf9Uy /languages/cpp.js
sha384-/yf54L01PbO6NtVs1Pu9rgfNHbKXanLdNcGVuNa0m5+KiyH+1NpZRDK6idm5VoVl /languages/cpp.min.js
sha384-h6xPJgkyvp13tIs697wZHjCH20tW1aJOrvnAKiZZiATSWZp0lyLB4bAdsEhWUSze /languages/css.js
sha384-+MO3D3y/aZzZq7QMAAA5KiuAcqBZivJHFmVUXfwdBoLxEXeGTeQGsNMll4fpnegg /languages/css.min.js
sha384-dMNLrPkwjJLQU3QnOACuNxKwF5uJKlgc1jxuGPSZgOTAhFFsakEk5maskn1jbxjY /languages/dart.js
sha384-xV+yQq6yNCJpHU1bXc40ygKBQS6BF2u/5RgLa0A64Rn/ue1fW52gr1gF8rko0wkG /languages/dart.min.js
sha384-cZ2d3Mo/jmTF9r2kHWcHmA8hehxX8N44UN6LSkEhaCRe6t8e9ntd5JEuafywm0aw /languages/java.js
sha384-8mc5ynnm3AlnXn8P3ccSqVAaZIDoijPM08/Hp4DABy6GMy7EHCQFwiIUoGAaGJiO /languages/java.min.js
sha384-p/utwvqrRVOLlz0BjJ0BCGCb2liTDipfz47/QmGXz9hoPIjCKYEgmYUC30VmGgZy /languages/javascript.js
sha384-L/XmDiyusXomLRGcRmcBpPlboRFjpQNV747OJvg+sEOpgGYvUsNwcC4JLNQ2dI6O /languages/javascript.min.js
sha384-psmmPlbfEWGyvRapexDqkVTgNz7Y1xvlGdLNWQSafI4GFQYFDXPZxVXH1laU4n6l /languages/json.js
sha384-Bb6DhE3tUpBROwypL78TbhRUs9QbCt2GxcxVSYglt2l3MefrYkm4CfwjfWhRfQaX /languages/json.min.js
sha384-Ve7wqoYcjaWimhzLnfK0sj2Lij8DmxK2diJ9kazkpifUrd7O+b2CbnHSxD3SCzqj /languages/kotlin.js
sha384-s0inyAR7LE5SVvn9VCZrQaiUxkDi+RsQdSKzFh2CjWf+LFd01DAjt9wtxGhT+4qT /languages/kotlin.min.js
sha384-TVvUXbmPgdS59xZSFUeyNQ1vUkeCbBpuMj3qlzdEwdQhoO5F/WNdI94UEw8g7Enp /languages/markdown.js
sha384-sFh+6oaRBb6kdaMLf8x7qeH7NTvm2u1Ta6PtI0S8hoA+bP7UtHCyKFzaI1JBXwhT /languages/markdown.min.js
sha384-v4qiQbdZu8obdLOFoHrZxA44mmxnjZUelyHe7A6RuqmckxO5weYQVrN8Dx2UpAR1 /languages/plaintext.js
sha384-hE+znpd5xggEBW6IccZoCI0mgFHAfLVuqT/7aW8RakaQ4UJnI058SfIX3lhdGxtE /languages/plaintext.min.js
sha384-/AFMsGSWoas65G5mSpnY9M1vnVP/9qhQW9yGZCpgbuL36JxWKX6MABh2hj6pc4yV /languages/powershell.js
sha384-0u0NM3ve01ej9h9zRzZ/ztDGe1h07d6TStpNoJ4f/50I/vtoCsDHI2PfzDZSYz8q /languages/powershell.min.js
sha384-WNah6F2QDUbmrNCi0fSEyKJbSb01S1ijnoiwbDnegW7dm2Cz/H1CiH1HhWlUvj01 /languages/python.js
sha384-YDj7s2Wf0QEwarV3OB8lvoNJJCH032vOLMDo2HDrYiEpQ+QmKN+e++x3hElX5S+w /languages/python.min.js
sha384-as0oqcSBkBCW8JS5FUngtpwqXH0qK8dlfpPE2IYoERAn+MRsJdlb89n/hgKYshzJ /languages/r.js
sha384-u+x0P8zfV33Hs+FIbrPIw38IUbqKyYA1yEdL911mrwtUJxaNJtMOdB2injOcZMmF /languages/r.min.js
sha384-1MNX8RDXroN7D+Jeq9f6EysUNAuhuQMq32wKcGB5yEDEJalUxEoSjfRVJhF0+YV6 /languages/scss.js
sha384-7CdPzO1jMDolQK+LCRlGiW1Oka6fSiQdIiqfTvHeBk2Hm2iYNoqMn60aJ9HdKkjb /languages/scss.min.js
sha384-KYOeDvyFo8fJObDV1L1aoPnfs6XG68LL6j3INM7McXyRYtBZF7DdUsNjK25dtxKo /languages/shell.js
sha384-olAuUjfRvTi/iEH4RXRpaq/G1iJGizn7OefkyJLQYuqNhh1xAV5dnUrkH/LlPd9j /languages/shell.min.js
sha384-w/OmtgUvmlKWaVatpcvuEQxP7bkJzI5gLeeQkuXjApJNiQvNmXFL2PBM5RWgKqDr /languages/sql.js
sha384-2uzCjI3OPwJce6i2hphsYs1qqTqRrDnfPXbfjZggPWy2/Lgl8gzV9Hyl0jhhoWy4 /languages/sql.min.js
sha384-avfxrZ7nwXDWWFaYzhYylhlr8UCb5MOAoBoIxEYvDmPl2iPfA/4qk4jrIYdyGVA0 /languages/swift.js
sha384-TfALNLT6HJzZieazgsVvFM0DzFWQsgl0d7mdwPLyg1yg7XE4QwLY4jqmJRNnI1S4 /languages/swift.min.js
sha384-4q0Mj1AHSvVdgi6nXDGdkiHZQcme/PcCE+MvwCvnAIZSjhJfk3UpjJU2nn2eImWz /languages/typescript.js
sha384-rfwxAwuWzb2XdSU7HN3IhrSyCq96Nj4p1ZYPCNAGbqtnPsaWl8d5eSypxPbW6alT /languages/typescript.min.js
sha384-6IMlY3eILHj9Dec4eMLmEQNsQF49OiTeVVMNIy1A+PxuMdmoeZ2AnVN/7FEpsgAx /languages/vim.js
sha384-vfNnhhcZoO470LVTMwy7VO8IGy2qRDfw+NOnU7pdz/V8y2uNfjq5Ea7Gljj0dZEn /languages/vim.min.js
sha384-QAL2h4IMgQaJUJjUy0dSWdAut7o/A272ai8qOsJ8SSm9KMxkdLgH7oGfLGft/EJ0 /languages/xml.js
sha384-CN3No+n1UZXCFYyl+ge5yAPGTNGuH23BdIsFJxntDmEYL94AmoZlNBHGSdjVSjKG /languages/xml.min.js
sha384-3KIoWvJ5JGRH35WAkzreEebY8sug+ZWeaOPS2r1KIfznEU9TtPFpxX6sIgtaiA9G /languages/yaml.js
sha384-bMkvdnz+wPu1ro0fqO3BaDWztc7RzSvw05MQFP6bhJKDcwpkrFYTfTFI9ndkP11l /languages/yaml.min.js
sha384-b5JxyhKxDXAP04F3EP1/F46S7cbZLSLivf6de4HPsRZ5imkpgOtoR1qEibNGj0VG /highlight.js
sha384-Di6GZebkopZ755uOD76QZ9rs67GC90efmE/4NYZPR8n260m9FumIfohu5Od1kUMl /highlight.min.js
```

