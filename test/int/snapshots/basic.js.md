# Snapshot report for `test/int/basic.js`

The actual snapshot is saved in `basic.js.snap`.

Generated by [AVA](https://ava.li).

## form body file

> Snapshot 1

    `// Auto-generated by the postman-to-k6 converter␊
    ␊
    import "./libs/shim/core.js";␊
    import http from "k6/http";␊
    ␊
    export let options = { maxRedirects: 4 };␊
    ␊
    const Request = Symbol.for("request");␊
    postman[Symbol.for("initial")]({␊
      options␊
    });␊
    ␊
    const files = {};␊
    files["theultimatequestion.txt"] = http.file(␊
      open("theultimatequestion.txt", "b"),␊
      "theultimatequestion.txt"␊
    );␊
    ␊
    export default function() {␊
      postman[Request]({␊
        name: "TestFileUpload",␊
        method: "POST",␊
        address: "http://deepthought.test/",␊
        data: {␊
          file: files["theultimatequestion.txt"]␊
        }␊
      });␊
    }␊
    `

## form body text

> Snapshot 1

    `// Auto-generated by the postman-to-k6 converter␊
    ␊
    import "./libs/shim/core.js";␊
    ␊
    export let options = { maxRedirects: 4 };␊
    ␊
    const Request = Symbol.for("request");␊
    postman[Symbol.for("initial")]({␊
      options␊
    });␊
    ␊
    export default function() {␊
      postman[Request]({␊
        name: "TestRequest",␊
        method: "POST",␊
        address: "http://example.com/",␊
        data: {␊
          first: "one",␊
          second: "two",␊
          third: "three"␊
        }␊
      });␊
    }␊
    `

## iterations

> Snapshot 1

    `// Auto-generated by the postman-to-k6 converter␊
    ␊
    import "./libs/shim/core.js";␊
    ␊
    export let options = { maxRedirects: 4, iterations: 25 };␊
    ␊
    const Request = Symbol.for("request");␊
    postman[Symbol.for("initial")]({␊
      options␊
    });␊
    ␊
    export default function() {␊
      postman[Request]({␊
        name: "TestRequest",␊
        method: "GET",␊
        address: "http://example.com/"␊
      });␊
    }␊
    `

## no body alternate

> Snapshot 1

    `// Auto-generated by the postman-to-k6 converter␊
    ␊
    import "./libs/shim/core.js";␊
    ␊
    export let options = { maxRedirects: 4 };␊
    ␊
    const Request = Symbol.for("request");␊
    postman[Symbol.for("initial")]({␊
      options␊
    });␊
    ␊
    export default function() {␊
      postman[Request]({␊
        name: "TestRequest",␊
        method: "GET",␊
        address: "http://example.com/"␊
      });␊
    }␊
    `

## raw body

> Snapshot 1

    `// Auto-generated by the postman-to-k6 converter␊
    ␊
    import "./libs/shim/core.js";␊
    ␊
    export let options = { maxRedirects: 4 };␊
    ␊
    const Request = Symbol.for("request");␊
    postman[Symbol.for("initial")]({␊
      options␊
    });␊
    ␊
    export default function() {␊
      postman[Request]({␊
        name: "TestRequest",␊
        method: "POST",␊
        address: "http://example.com/",␊
        data: "line1\\nline2\\nline3\\n"␊
      });␊
    }␊
    `

## request

> Snapshot 1

    `// Auto-generated by the postman-to-k6 converter␊
    ␊
    import "./libs/shim/core.js";␊
    ␊
    export let options = { maxRedirects: 4 };␊
    ␊
    const Request = Symbol.for("request");␊
    postman[Symbol.for("initial")]({␊
      options␊
    });␊
    ␊
    export default function() {␊
      postman[Request]({␊
        name: "TestRequest",␊
        method: "GET",␊
        address: "http://example.com/"␊
      });␊
    }␊
    `

## url body

> Snapshot 1

    `// Auto-generated by the postman-to-k6 converter␊
    ␊
    import "./libs/shim/core.js";␊
    ␊
    export let options = { maxRedirects: 4 };␊
    ␊
    const Request = Symbol.for("request");␊
    postman[Symbol.for("initial")]({␊
      options␊
    });␊
    ␊
    export default function() {␊
      postman[Request]({␊
        name: "TestRequest",␊
        method: "POST",␊
        address: "http://example.com/",␊
        data: {␊
          first: "one",␊
          second: "two",␊
          third: "three"␊
        },␊
        headers: {␊
          "Content-Type": "application/x-www-form-urlencoded"␊
        }␊
      });␊
    }␊
    `