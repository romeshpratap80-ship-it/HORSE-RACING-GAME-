<!DOCTYPE html>
<html lang="en"><head><script data-bard-client-injected="true">(function(firebaseConfig, initialAuthToken, appId) {
        window.__firebase_config = firebaseConfig;
        window.__initial_auth_token = initialAuthToken;
        window.__app_id = appId;
            })("\n{\n  \"apiKey\": \"AIzaSyCqyCcs2R2e7AegGjvFAwG98wlamtbHvZY\",\n  \"authDomain\": \"bard-frontend.firebaseapp.com\",\n  \"projectId\": \"bard-frontend\",\n  \"storageBucket\": \"bard-frontend.firebasestorage.app\",\n  \"messagingSenderId\": \"175205271074\",\n  \"appId\": \"1:175205271074:web:2b7bd4d34d33bf38e6ec7b\"\n}\n","eyJhbGciOiJSUzI1NiIsImtpZCI6IjExNjRiNzdiNDMzZDdhMDAyMWI4NjE4YjhjYTU3ZTMyZGI5MWUxMTMiLCJ0eXAiOiJKV1QifQ.eyJzdWIiOiJmaXJlYmFzZS1hZG1pbnNkay1mYnN2Y0BiYXJkLWZyb250ZW5kLmlhbS5nc2VydmljZWFjY291bnQuY29tIiwiYXVkIjoiaHR0cHM6Ly9pZGVudGl0eXRvb2xraXQuZ29vZ2xlYXBpcy5jb20vZ29vZ2xlLmlkZW50aXR5LmlkZW50aXR5dG9vbGtpdC52MS5JZGVudGl0eVRvb2xraXQiLCJ1aWQiOiIxNjI0MjI2MTk4MTM0ODc4NDIwNiIsImlzcyI6ImZpcmViYXNlLWFkbWluc2RrLWZic3ZjQGJhcmQtZnJvbnRlbmQuaWFtLmdzZXJ2aWNlYWNjb3VudC5jb20iLCJjbGFpbXMiOnsiYXBwSWQiOiJjXzU2ZWE1YTFkMWRhNjMwMDVfaG9yc2VfcmlkaW5nLmh0bWwtNjcifSwiZXhwIjoxNzk1NDE3OTczLCJpYXQiOjE3OTU0MTQzNzMsImFsZyI6IlJTMjU2In0.EKtjgseqkdDZKBjvU0OQtyX0EwuFjaq6HccX8_ykJI2Sb9NDcTRZDajSLG3i3iynpQtxMSEWS-E_QuvOE-XxOTHhZI3XSsW0mMXYsCiUKImp8rWfiLyDA_gHuq6qwjeGkR-N71U6PDGi-eFnd-5QueymwiByK9F1kgRvEfJPeXBnWhXQi1AD_vMTP7d14WC9IaaJhUhzkFCYwCrKLhdGQmpbO_sSAr5iAK6CWf_mra3oZ1-j49YbzPyz0xYsGmwYhCX2fkIVuPII7fwCQqLPsRBpg4EZMihCJJ2OIvb0Oc_iEHMZsAp8HV1hXM9AA4gyAZ4tmTTttMBNvOBHX76uIQ","c_56ea5a1d1da63005_horse_riding.html-67")</script><script data-bard-client-injected="true">
  document.addEventListener('input', (event) => {
    if (event.target && (event.target.isContentEditable || event.target.hasAttribute('contenteditable'))) {
      const clonedDoc = document.cloneNode(true);
      const injectedScripts = clonedDoc.querySelectorAll('[data-bard-client-injected="true"]');
      injectedScripts.forEach(el => el.remove());
      window.parent.postMessage({
        type: 'inlineEdit',
        html: '<!DOCTYPE html>\n' + clonedDoc.documentElement.outerHTML
      }, '*');
    }
  });
</script><script data-bard-client-injected="true">(function(){'use strict';window.addEventListener("message",a=>{a.data&&a.data.type==="SUPPLEMENTAL_DATA_UPDATE"&&window.dispatchEvent(new CustomEvent("supplementaldataupdate",{detail:a.data.data}))});}).call(this);
</script><script data-bard-client-injected="true">(function() {
  const SCROLL_KEYS = new Set([
    'ArrowUp', 'ArrowDown', 'ArrowLeft', 'ArrowRight',
    ' ', 'Spacebar', 'PageUp', 'PageDown', 'Home', 'End',
  ]);
  const HORIZONTAL_KEYS = new Set(['ArrowLeft', 'ArrowRight']);

  function isTextEntryTarget(target) {
    if (!target) return false;
    const tagName = target.tagName;
    return tagName === 'INPUT' || tagName === 'TEXTAREA' ||
        tagName === 'SELECT' || target.isContentEditable === true;
  }

  // An element absorbs the key only if it both overflows on the axis being
  // scrolled and is configured to scroll on that axis. The cheap dimension
  // test runs first because getComputedStyle forces a style recalc, and this
  // runs on every keypress. Each axis is read from its own longhand: the
  // 'overflow' shorthand serializes as two values when the axes differ, which
  // is the common 'overflow-x: hidden; overflow-y: auto' pane.
  function canScroll(node, horizontal) {
    const overflows = horizontal ? node.scrollWidth > node.clientWidth
                                 : node.scrollHeight > node.clientHeight;
    if (!overflows) return false;
    const style = window.getComputedStyle(node);
    const overflow = horizontal ? style.overflowX : style.overflowY;
    return overflow === 'auto' || overflow === 'scroll';
  }

  // Walks up from the event target so nested scrollers keep their behavior.
  // <body> is included because pages that pin the root height make it the
  // scroll container.
  function hasScrollableAncestor(target, horizontal) {
    let node = target;
    while (node && node !== document.documentElement) {
      if (canScroll(node, horizontal)) return true;
      node = node.parentElement;
    }
    return false;
  }

  function rootCanScroll(horizontal) {
    const scroller = document.scrollingElement || document.documentElement;
    if (!scroller) return false;
    // Tolerate a pixel of rounding so subpixel layouts do not look scrollable.
    return horizontal ? scroller.scrollWidth > window.innerWidth + 1
                      : scroller.scrollHeight > window.innerHeight + 1;
  }

  window.addEventListener('keydown', function(event) {
    if (!SCROLL_KEYS.has(event.key)) return;
    if (event.defaultPrevented) return;
    // Alt and Meta turn arrows into browser history navigation, and Ctrl is
    // reserved for shortcuts, so none of them are scroll intent.
    if (event.altKey || event.metaKey || event.ctrlKey) return;

    const target = event.target;
    if (isTextEntryTarget(target)) return;

    // Anything that can still absorb the scroll gets to keep it.
    const horizontal = HORIZONTAL_KEYS.has(event.key);
    if (rootCanScroll(horizontal)) return;
    if (hasScrollableAncestor(target, horizontal)) return;

    event.preventDefault();
  }, {capture: true, passive: false});
})();</script><script data-bard-client-injected="true">(function() {
  // Ensure this script is executed only once
  if (window.firebaseAuthBridgeScriptLoaded) {
    return;
  }
  window.firebaseAuthBridgeScriptLoaded = true;

  let nextTokenPromiseId = 0;

  // Stores { resolve, reject } for ongoing token requests
  const pendingTokenPromises = {};

  // Listen for messages from the Host Application
  window.addEventListener('message', function(event) {

    const messageData = event.data;

  if (messageData && messageData.type === 'RESOLVE_NEW_FIREBASE_TOKEN') {
      const { success, token, error, promiseId } = messageData ?? {};
      if (pendingTokenPromises[promiseId]) {
        if (success) {
          pendingTokenPromises[promiseId].resolve(token);
        } else {
          pendingTokenPromises[promiseId].reject(new Error(error || 'Token refresh failed from host.'));
        }
        delete pendingTokenPromises[promiseId];
      }
    }
  });

  // Expose a function for the Generated App to request a new Firebase token
  window.requestNewFirebaseToken = function() {
    const currentPromiseId = nextTokenPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingTokenPromises[currentPromiseId] = { resolve, reject };
    });
    if (window.parent && window.parent !== window) {
      window.parent.postMessage({
        type: 'REQUEST_NEW_FIREBASE_TOKEN',
        promiseId: currentPromiseId
      }, '*');
    } else {
      pendingTokenPromises[currentPromiseId].reject(new Error('No parent window to request token from.'));
      delete pendingTokenPromises[currentPromiseId];
    }
    return promise;
  };
})();</script><script data-bard-client-injected="true">
let realOriginalGetUserMedia = null;
if (navigator.mediaDevices && navigator.mediaDevices.getUserMedia) {
  realOriginalGetUserMedia = navigator.mediaDevices.getUserMedia.bind(navigator.mediaDevices);
}

(function() {
  if (navigator.mediaDevices && navigator.mediaDevices.__proto__) {
    try {
      Object.defineProperty(navigator.mediaDevices.__proto__, 'getUserMedia', {
        get: function() {
          return undefined; // Or throw an error
        },
        configurable: false
      });
    } catch (error) {
      console.error("Error defining prototype getter:", error);
    }
  }
})();

(function() {
  const pendingMediaResolvers = {};
  let nextMediaPromiseId = 0;

  function requestMediaPermissions(constraints) {
    const mediaPromiseId = nextMediaPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingMediaResolvers[mediaPromiseId] = (granted) => {
        delete pendingMediaResolvers[mediaPromiseId];
        resolve(granted);
      };
    });

    window.parent.postMessage({
      type: 'requestMediaPermission',
      constraints: constraints,
      promiseId: mediaPromiseId,
    }, '*');

    return promise;
  }

  let originalGetUserMedia = realOriginalGetUserMedia;

  function interceptGetUserMedia() {
    if (navigator.mediaDevices) {
      Object.defineProperty(navigator.mediaDevices, 'getUserMedia', {
        value: function(constraints) {
          return requestMediaPermissions(constraints).then((granted) => {
            if (granted) {
              if (originalGetUserMedia) {
                return originalGetUserMedia(constraints);
              } else {
                throw new Error("Original getUserMedia not available.");
              }
            } else {
              throw new DOMException('Permission denied', 'NotAllowedError');
            }
          });
        },
        writable: false,
        configurable: false
      });
    }
  }

  interceptGetUserMedia();

  const observer = new MutationObserver(function(mutationsList, observer) {
    for (const mutation of mutationsList) {
      if (mutation.type === 'reconfigured' && mutation.name === 'getUserMedia' && mutation.object === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'attributes' && mutation.attributeName === 'getUserMedia' && mutation.target === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'childList' && mutation.addedNodes) {
        mutation.addedNodes.forEach(node => {
          if (node === navigator.mediaDevices) {
            interceptGetUserMedia();
          }
        });
      }
    }
  });

  function interceptSpeechRecognition() {
    if (!window.SpeechRecognition && !window.webkitSpeechRecognition) {
      return;
    }

    const OriginalSpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;

    const SpeechRecognitionWrapper = function(...args) {
      const recognizer = new OriginalSpeechRecognition(...args);
      const originalStart = recognizer.start.bind(recognizer);

      recognizer.start = function() {
        requestMediaPermissions({ audio: true }).then(granted => {
          if (granted) {
            originalStart();
          } else {
            const errorEvent = new SpeechRecognitionErrorEvent('error');
            errorEvent.error = 'not-allowed'; // This is the standard error for permission denial.
            recognizer.dispatchEvent(errorEvent);
          }
        });
      };

      return recognizer;
    };

    SpeechRecognitionWrapper.prototype = OriginalSpeechRecognition.prototype;
    SpeechRecognitionWrapper.prototype.constructor = SpeechRecognitionWrapper;

    if (window.SpeechRecognition) {
      window.SpeechRecognition = SpeechRecognitionWrapper;
    }
    if (window.webkitSpeechRecognition) {
      window.webkitSpeechRecognition = SpeechRecognitionWrapper;
    }
  }

  interceptSpeechRecognition();

  window.addEventListener('message', function(event) {
    if (event.data) {
      if (event.data.type === 'resolveMediaPermission') {
        const { promiseId, granted } = event.data;
        if (pendingMediaResolvers[promiseId]) {
          pendingMediaResolvers[promiseId](granted);
        }
      }
    }
  });

})();</script><script ws-interception-config="{&quot;parentOrigin&quot;:&quot;https://gemini.google.com&quot;,&quot;proxiedDomains&quot;:[]}" data-bard-client-injected="true">(function(){'use strict';var u=typeof Object.defineProperties=="function"?Object.defineProperty:function(b,d,e){if(b==Array.prototype||b==Object.prototype)return b;b[d]=e.value;return b};function v(b){b=["object"==typeof globalThis&&globalThis,b,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var d=0;d<b.length;++d){var e=b[d];if(e&&e.Math==Math)return e}throw Error("Cannot find global object");}var w=v(this);
function y(b,d){if(d)a:{var e=w;b=b.split(".");for(var h=0;h<b.length-1;h++){var k=b[h];if(!(k in e))break a;e=e[k]}b=b[b.length-1];h=e[b];d=d(h);d!=h&&d!=null&&u(e,b,{configurable:!0,writable:!0,value:d})}}function z(b){function d(h){return b.next(h)}function e(h){return b.throw(h)}return new Promise(function(h,k){function m(n){n.done?h(n.value):Promise.resolve(n.value).then(d,e).then(m,k)}m(b.next())})}y("globalThis",function(b){return b||w});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
function A(b,d){function e(){}e.prototype=d.prototype;b.i=d.prototype;b.prototype=new e;b.prototype.constructor=b;b.h=function(h,k,m){for(var n=Array(arguments.length-2),p=2;p<arguments.length;p++)n[p-2]=arguments[p];return d.prototype[k].apply(h,n)}};function B(b,d,e="*"){function h(a){if(typeof a==="string")return F.encode(a).buffer;if(a instanceof ArrayBuffer)return a.slice(0);if(ArrayBuffer.isView(a))return a.buffer.slice(a.byteOffset,a.byteOffset+a.byteLength);throw Error("Invalid data type");}function k(a){a=h(a);var f={type:"send",data:new Uint8Array(a)},g;(g=r)==null||g.postMessage(f,[a])}function m(){if(!r)throw Error("Data port not captured yet.");r.onmessage=a=>{if(a.data.type==="message"){a=new MessageEvent("message",{data:G.decode(a.data.data)});
let f;(f=c.onmessage)==null||f.call(c,a);c.dispatchEvent(a)}}}function n(){if(!t)throw Error("Control port not captured yet.");t.onmessage=a=>{switch(a.data.type){case "open":l=1;var f=new Event("open"),g;(g=c.onopen)==null||g.call(c,f);c.dispatchEvent(f);q.forEach(H=>{k(H)});q=[];break;case "close":g=a.data;l=3;g=new CloseEvent("close",{code:g.code,reason:g.reason,wasClean:g.wasClean});(f=c.onclose)==null||f.call(c,g);c.dispatchEvent(g);break;case "error":l=3;f=new Event("error");let x;(x=c.onerror)==
null||x.call(c,f);c.dispatchEvent(f)}}}function p(a){return z(function*(){var f=new MessageChannel;t=f.port1;var g=new MessageChannel;r=g.port1;n();m();window.parent.postMessage({type:"websocket_open",portOrdering:["control","data"],url:b,protocols:a||[],connectionId:I},e,[f.port2,g.port2])}())}var c=Reflect.construct(EventTarget,[],new.target);c.CONNECTING=0;c.OPEN=1;c.CLOSING=2;c.CLOSED=3;c.url=b;c.binaryType="arraybuffer";c.protocol="";c.extensions="";var l=0,t=null,r=null,q=[],F=new TextEncoder,
G=new TextDecoder;c.onopen=null;c.onmessage=null;c.onclose=null;c.onerror=null;Object.defineProperty(c,"readyState",{get:()=>l,enumerable:!0,configurable:!0});Object.defineProperty(c,"bufferedAmount",{get:()=>{var a=0;q.forEach(f=>{a+=typeof f==="string"?f.length:f.byteLength});return a},enumerable:!0,configurable:!0});var I=function(){var a;return((a=globalThis.crypto)==null?0:a.randomUUID)?globalThis.crypto.randomUUID():"xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g,f=>{var g=Math.random()*
16|0;return(f==="x"?g:g&3|8).toString(16)})}();c.send=a=>{if(l===1)a instanceof Blob?a.arrayBuffer().then(f=>{k(f)}):k(a);else if(l===0)if(typeof a==="string")q.push(a);else if(a instanceof ArrayBuffer||ArrayBuffer.isView(a))q.push(h(a));else throw Error("Sending Blob is not supported before the connection is open.");else console.debug("WebSocket send called in CLOSING or CLOSED state; ignored.")};c.close=(a=1E3,f="")=>{if(l!==2&&l!==3){l=2;a={type:"close",code:a,reason:f,wasClean:a===1E3};var g;
(g=t)==null||g.postMessage(a)}};Promise.resolve().then(()=>p(d));return c}A(B,EventTarget);var C=document.currentScript,D=C==null?void 0:C.getAttribute("ws-interception-config");if(!D)throw Error("WebSocket Interceptor: Missing ws-interception-config attribute in the script tag.");var E=JSON.parse(D);if(!E.parentOrigin||typeof E.parentOrigin!=="string")throw Error("WebSocket Interceptor: Invalid parentOrigin in ws-interception-config");
(function(b){var d=Object.getOwnPropertyDescriptor(window,"WebSocket");if(!d||d.writable||d.configurable)d=Object.assign(function(e,h){try{let k=(new URL(e)).hostname;if(b.proxiedDomains.some(m=>k===m||k.endsWith(`.${m}`)))return new B(e,h,b.parentOrigin)}catch(k){throw window.parent.postMessage({type:"websocket_blocked",url:e,reason:"blocked_invalid_url"},b.parentOrigin),new DOMException(`WebSocket connection to '${e}' is not allowed in Canvas.`,"SecurityError");}window.parent.postMessage({type:"websocket_blocked",
url:e,reason:"blocked_domain_not_allowlisted"},b.parentOrigin);throw new DOMException(`WebSocket connection to '${e}' is not allowed in Canvas.`,"SecurityError");},{CONNECTING:0,OPEN:1,CLOSING:2,CLOSED:3}),Object.defineProperty(window,"WebSocket",{value:d,writable:!1,configurable:!1})})({proxiedDomains:E.proxiedDomains||[],parentOrigin:E.parentOrigin});}).call(this);
</script><script data-bard-client-injected="true">((function(modelInformation) {
  const originalFetch = window.fetch;
  // TODO: b/421908508 - Move these out of the script and match all generative AI model calls.
  let googleLlmBaseApiUrls = [
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':streamGenerateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageEditModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageTransformModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.ttsModelName + ':generateContent',
  ];
  modelInformation.deprecatedTextModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
    );
  });
  modelInformation.deprecatedImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predict',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predictLongRunning',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });
  modelInformation.deprecatedGenerateImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });
  modelInformation.deprecatedImageTransformModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });

  const pendingFetchResolvers = {};
  let nextPromiseId = 0;

  function handleStringInput(input, optionsArgument) {
    const actualUrl = input;
    const fetchCallArgs = [actualUrl, optionsArgument];
    const effectiveOptions = optionsArgument || {};
    const bodyForApiKeyCheck = effectiveOptions.body;
    const bodyForPostMessage = effectiveOptions.body;
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  function handleRequestInput(input, optionsArgument) {
    const actualUrl = input.url;
    const fetchCallArgs = [input, optionsArgument];
    const effectiveOptions = { method: input.method, headers: new Headers(input.headers) };
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (optionsArgument) {
      if (optionsArgument.method) effectiveOptions.method = optionsArgument.method;
      if (optionsArgument.headers) effectiveOptions.headers = new Headers(optionsArgument.headers);
      if ('body' in optionsArgument) {
        bodyForApiKeyCheck = optionsArgument.body;
        bodyForPostMessage = optionsArgument.body;
      } else {
        bodyForApiKeyCheck = undefined;
        bodyForPostMessage = input.body;
      }
    } else {
      bodyForApiKeyCheck = undefined;
      bodyForPostMessage = input.body;
    }
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  window.fetch = function(input, optionsArgument) {
    let actualUrl;
    let fetchCallArgs;
    let effectiveOptions = {};
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (typeof input === 'string') {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleStringInput(input, optionsArgument));
    } else if (input instanceof Request) {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleRequestInput(input, optionsArgument));
    } else {
      return originalFetch.apply(window, [input, optionsArgument]);
    }

    effectiveOptions.method = effectiveOptions.method || 'GET';
    if (!effectiveOptions.headers) {
      effectiveOptions.headers = new Headers();
    }


    if (typeof actualUrl === 'string' && googleLlmBaseApiUrls.some((url) => actualUrl.startsWith(url))) {
      let apiKeyIsNull = true;

      const regex = new RegExp("models/([^:]+)");
      const modelNameMatch = actualUrl.match(regex);
      const modelName = modelNameMatch ? modelNameMatch[1] : 'unspecified';


      try {
        const urlObject = new URL(actualUrl);  // Use URL object for robust parsing
        const apiKeyParam = urlObject.searchParams.get('key');
        if (apiKeyParam) {
          apiKeyIsNull = false;
        }
      } catch (e) {
        // Continue checks even if URL parsing fails
      }

      if (apiKeyIsNull && effectiveOptions.headers) {
        const h = new Headers(effectiveOptions.headers);
        const apiKeyHeaderValue = h.get('X-API-Key') || h.get('x-api-key');
        if (apiKeyHeaderValue) {
          apiKeyIsNull = false;
          return originalFetch.apply(window, fetchCallArgs);
        }
      }

      if (apiKeyIsNull && effectiveOptions.method && ['POST', 'PUT', 'PATCH'].includes(effectiveOptions.method.toUpperCase()) && typeof bodyForApiKeyCheck === 'string') {
        try {
          const bodyData = JSON.parse(bodyForApiKeyCheck);
          if (bodyData && bodyData.apiKey) {
            apiKeyIsNull = false;
            return originalFetch.apply(window, fetchCallArgs);
          }
        } catch (e) {
          // Ignore JSON parsing errors
        }
      }

      if(apiKeyIsNull) {
        const promiseId = nextPromiseId++;
        const promise = new Promise((resolve) => {
          pendingFetchResolvers[promiseId] = (resolvedResponse) => {
            delete pendingFetchResolvers[promiseId];
            resolve(resolvedResponse);
          };
        });

        let serializedBodyForPostMessage;
        if (typeof bodyForPostMessage === 'string' || bodyForPostMessage == null) {
            serializedBodyForPostMessage = bodyForPostMessage;
        } else if (bodyForPostMessage instanceof ReadableStream) {
            serializedBodyForPostMessage = null;
        } else {
            try {
                serializedBodyForPostMessage = JSON.stringify(bodyForPostMessage);
            } catch (e) {
                serializedBodyForPostMessage = null;
            }
        }

        const messageOptions = {
            method: effectiveOptions.method,
            headers: Object.fromEntries(new Headers(effectiveOptions.headers).entries()),
            body: serializedBodyForPostMessage
        };

        window.parent.postMessage({
          type: 'requestFetch',
          url: actualUrl,
          modelName: modelName,
          options: messageOptions,
          promiseId: promiseId,
        }, '*');

        return promise;
      }
      return originalFetch.apply(window, fetchCallArgs);
    }
    return originalFetch.apply(window, fetchCallArgs);
  };

  window.addEventListener('message', function(event) {
    if (event.data && event.data.type === 'resolveFetch') {
      const { promiseId, response } = event.data;
      if (pendingFetchResolvers[promiseId]) {
        try {
          const reconstructedResponse = new Response(response.body, {
            status: response.status,
            statusText: response.statusText,
            headers: new Headers(response.headers),
          });
          pendingFetchResolvers[promiseId](reconstructedResponse);
        } catch (error) {
          pendingFetchResolvers[promiseId](new Response(null, { status: 500, statusText: "Interceptor Response Reconstruction Error" }));
        }
      }
    }
  });

}))({"textModelName":"gemini-3-flash-preview","imageModelName":"imagen-4.0-generate-001","imageEditModelName":"gemini-3.1-flash-image","imageTransformModelName":"gemini-3-pro-image","videoModelName":"veo-2.0-generate-001","ttsModelName":"gemini-2.5-flash-preview-tts","deprecatedTextModelNames":["gemini-2.0-flash","gemini-2.5-flash","gemini-2.5-flash-preview-04-17","gemini-2.5-flash-preview-05-20","gemini-2.5-flash-preview-09-2025"],"deprecatedImageModelNames":["imagen-3.0-generate-001","imagen-3.0-generate-002"],"deprecatedGenerateImageModelNames":["gemini-2.5-flash-image-preview","gemini-2.5-flash-image","gemini-3.1-flash-image-preview"],"deprecatedImageTransformModelNames":["gemini-3-pro-image-preview-11-2025"]})</script><script data-bard-client-injected="true">(function() {
  const OVERLAY_SELECTOR =
    'dialog[open], [role="dialog"], [role="alertdialog"], [role="menu"], [role="listbox"], [role="combobox"]';

  function isVisibleOverlay(element) {
    if (element.closest('[hidden], [aria-hidden="true"], [inert]')) {
      return false;
    }
    if (window.getComputedStyle(element).visibility === 'hidden') {
      return false;
    }
    for (let cur = element; cur; cur = cur.parentElement) {
      if (window.getComputedStyle(cur).display === 'none') {
        return false;
      }
    }
    return true;
  }

  function hasOpenOverlay() {
    const candidates = document.querySelectorAll(OVERLAY_SELECTOR);
    for (let i = 0; i < candidates.length; i++) {
      if (isVisibleOverlay(candidates[i])) {
        return true;
      }
    }
    try {
      if (document.querySelector('[popover]:popover-open')) {
        return true;
      }
    } catch (e) {
      // Ignore engines that do not support :popover-open.
    }
    return false;
  }

  function isNonEmptySearchInput(target) {
    return (
      Boolean(target) &&
      target.tagName === 'INPUT' &&
      typeof target.type === 'string' &&
      target.type.toLowerCase() === 'search' &&
      typeof target.value === 'string' &&
      target.value.length > 0
    );
  }

  function shouldIgnoreEscape(event) {
    return (
      event.key !== 'Escape' ||
      event.altKey ||
      event.ctrlKey ||
      event.metaKey ||
      event.shiftKey ||
      event.isComposing ||
      event.repeat ||
      event.keyCode === 229 ||
      isNonEmptySearchInput(event.target)
    );
  }

  let shouldIgnoreCaptureState = false;

  window.addEventListener(
    'keydown',
    function(event) {
      if (event.key === 'Escape') {
        shouldIgnoreCaptureState =
          hasOpenOverlay() || isNonEmptySearchInput(event.target);
      }
    },
    {capture: true},
  );

  window.addEventListener('keydown', function(event) {
    if (
      shouldIgnoreEscape(event) ||
      event.defaultPrevented ||
      shouldIgnoreCaptureState
    ) {
      return;
    }
    const wasBlockedOnCapture = shouldIgnoreCaptureState;
    queueMicrotask(function() {
      if (event.defaultPrevented || wasBlockedOnCapture) {
        return;
      }
      if (window.parent && window.parent !== window) {
        window.parent.postMessage({'type': 'escapeKey'}, '*');
      }
    });
  });
})();</script><script data-bard-client-injected="true">(function() {
  function normalizeSlug(str) {
    try {
      return str
        .trim()
        .toLowerCase()
        .replace(/[^p{L}p{N}s_-]/gu, '')
        .replace(/s+/g, '-');
    } catch (e) {
      return str
        .trim()
        .toLowerCase()
        .replace(/[^a-z0-9s_-]/g, '')
        .replace(/s+/g, '-');
    }
  }

  function findTargetElement(hash) {
    if (!hash || hash === '#') {
      return null;
    }
    const rawId = hash.startsWith('#') ? hash.slice(1) : hash;
    let decodedId = rawId;
    try {
      decodedId = decodeURIComponent(rawId);
    } catch (e) {
      // Ignore URI malformed errors.
    }

    // 1. Direct ID match (raw and decoded).
    let target = document.getElementById(rawId) || document.getElementById(decodedId);
    if (target) {
      return target;
    }

    // 2. Name attribute match (<a name="...">).
    try {
      if (typeof CSS !== 'undefined' && CSS.escape) {
        target =
          document.querySelector('[name="' + CSS.escape(rawId) + '"]') ||
          document.querySelector('[name="' + CSS.escape(decodedId) + '"]');
      } else {
        const namedElements = document.getElementsByName(rawId);
        if (namedElements && namedElements.length > 0) {
          return namedElements[0];
        }
      }
    } catch (e) {
      // Ignore querySelector syntax errors.
    }
    if (target) {
      return target;
    }

    // 3. Match heading text by slug (for Markdown TOCs where headings lack explicit IDs).
    const targetSlug = normalizeSlug(decodedId);
    if (targetSlug) {
      for (const heading of document.querySelectorAll('h1, h2, h3, h4, h5, h6')) {
        if (normalizeSlug(heading.textContent || '') === targetSlug) {
          return heading;
        }
      }
    }

    return null;
  }

  document.addEventListener('click', function(event) {
    const target = event.target;
    const anchor = target && typeof target.closest === 'function' ? target.closest('a') : null;
    if (!anchor) {
      return;
    }

    const href = anchor.getAttribute('href');
    if (
      !href ||
      href.trim().toLowerCase().startsWith('javascript:') ||
      anchor.hasAttribute('download')
    ) {
      return;
    }

    // Check if the link is an in-page hash / anchor link.
    if (href.startsWith('#')) {
      event.preventDefault();
      const targetElement = findTargetElement(href);
      if (targetElement) {
        targetElement.scrollIntoView({behavior: 'smooth', block: 'start'});
      }
      return;
    }

    // Check if the URL has the same origin/pathname but with a hash.
    try {
      const url = new URL(anchor.href, window.location.href);
      if (
        url.hash &&
        url.origin === window.location.origin &&
        url.pathname === window.location.pathname
      ) {
        event.preventDefault();
        const targetElement = findTargetElement(url.hash);
        if (targetElement) {
          targetElement.scrollIntoView({behavior: 'smooth', block: 'start'});
        }
        return;
      }
    } catch (e) {
      // Fall through if URL parsing fails.
    }

    // For all external or full navigation links, prevent iframe-level navigation
    // (which breaks in AGSA WebView or sandboxed iframes) and ensure they open
    // safely in a new tab/window.
    if (anchor.target !== '_blank') {
      event.preventDefault();
      window.open(anchor.href, '_blank', 'noopener,noreferrer');
    }
  }, {capture: true});
})();</script><script data-bard-client-injected="true">(function(){'use strict';function a(){window.parent.postMessage({type:"interaction"},"*")}window.addEventListener("click",a,{capture:!0,passive:!0});window.addEventListener("touchstart",a,{capture:!0,passive:!0});window.addEventListener("keydown",a,{capture:!0,passive:!0});}).call(this);
</script><script data-bard-client-injected="true">(function() {
  const originalConsoleLog = console.log;
  const originalConsoleError = console.error;

    /**
   * Normalizes an error event or a promise rejection reason into a structured error object.
   * @param {*} errorEventOrReason The error object or reason.
   * @return {object} Structured error data { message, name, stack }.
   */
  function getErrorObject(errorEventOrReason) {
    if (errorEventOrReason instanceof Error) {
      return {
        message: errorEventOrReason.message,
        name: errorEventOrReason.name,
        stack: errorEventOrReason.stack,
      };
    }
    // Fallback for non-Error objects.
    try {
      return {
        message: JSON.stringify(errorEventOrReason),
        name: 'UnknownErrorType',
        stack: null,
      };
    } catch (e) {
      return {
        message: String(errorEventOrReason),
        name: 'UnknownErrorTypeNonStringifiable',
        stack: null,
      };
    }
  }

  /**
   * Converts an array of arguments (from log/error) into a single string.
   * Handles Error objects specially to include their message and stack.
   * @param {Array<*>} args - Arguments passed to console methods.
   * @return {string} A string representation of the arguments.
   */
  function stringifyArgs(args) {
    return args
      .map((arg) => {
        if (arg instanceof Error) {
          const {message, stack} = arg;
          return `Error: ${message}${stack ? ('\nStack: ' + stack) : ''}`;
        }
        if (typeof arg === 'object' && arg !== null) {
          try {
            return JSON.stringify(arg);
          } catch (error) {
            return '[Circular Object]';
          }
        } else {
          return String(arg);
        }
      })
      .join(' ');
  }

  console.log = function(...args) {
    const logString = stringifyArgs(args);
    window.parent.postMessage({ type: 'log', message: logString }, '*');
    originalConsoleLog.apply(console, args);
  };

  console.error = function(...args) {
    let errorData;
    if (args.length > 0 && args[0] instanceof Error) {
      const err = args[0];
      // If the first arg is an Error, capture its details.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        ...getErrorObject(err),
        rawArgsString: stringifyArgs(args.slice(1)),
        timestamp: new Date().toISOString(),
      };
    } else {
      // If not an Error object, treat all args as a general error message.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        message: stringifyArgs(args),
        name: 'ConsoleLoggedError',
        stack: null,
        timestamp: new Date().toISOString(),
      };
    }
    window.parent.postMessage(errorData, '*');
    originalConsoleError.apply(console, args);
  };

  // Listen for global unhandled synchronous errors.
  window.addEventListener('error', function(event) {
    const errorDetails = event.error ? getErrorObject(event.error) : {
      message: event.message,
      name: 'GlobalError',
      stack: null,
      filename: event.filename,
      lineno: event.lineno,
      colno: event.colno,
    };

    window.parent.postMessage({
      type: 'error',
      source: 'global',
      ...errorDetails,
      message: errorDetails.message || event.message,
      timestamp: new Date().toISOString(),
    }, '*');
  });

  // Listen for unhandled promise rejections (asynchronous errors).
  window.addEventListener('unhandledrejection', function(event) {
    const errorDetails = getErrorObject(event.reason);

    window.parent.postMessage({
      type: 'error',
      source: 'unhandledrejection',
      ...errorDetails,
      message: errorDetails.message || 'Unhandled Promise Rejection',
      timestamp: new Date().toISOString(),
    }, '*');
  });

})();</script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Derby Dash - Horse Riding Game</title>
    <!-- Tailwind CSS for responsive HUD and controls -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome for crisp UI icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Tone.js for procedural hoofbeats, jump whooshes, and chime audio -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tone/14.8.49/Tone.js" crossorigin="anonymous"></script>
    <!-- Google Fonts: Fredoka & Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@600;700&amp;family=Inter:wght@400;600;700&amp;display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(180deg, #0f172a 0%, #1e293b 100%);
            color: #f8fafc;
            min-height: 100vh;
            overflow-x: hidden;
            user-select: none;
            -webkit-tap-highlight-color: transparent;
        }

        .font-game {
            font-family: 'Fredoka', sans-serif;
        }

        /* Responsive Canvas Container */
        .game-frame {
            position: relative;
            width: min(95vw, 960px);
            aspect-ratio: 16 / 9;
            max-height: 62vh;
            border-radius: 1.25rem;
            overflow: hidden;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.75), 0 0 0 4px #334155;
            background: #38bdf8;
        }

        @media (max-width: 640px) {
            .game-frame {
                aspect-ratio: 4 / 3;
                max-height: 56vh;
            }
        }

        canvas {
            display: block;
            width: 100%;
            height: 100%;
            touch-action: none;
        }

        /* Tactile Arcade Buttons */
        .arcade-btn {
            background: linear-gradient(180deg, #334155 0%, #1e293b 100%);
            border: 1px solid #475569;
            box-shadow: 0 5px 0 #0f172a, 0 8px 16px rgba(0, 0, 0, 0.4);
            transition: transform 0.08s ease, box-shadow 0.08s ease, filter 0.15s ease;
        }
        .arcade-btn:hover:not(:disabled) {
            filter: brightness(1.1);
            transform: translateY(-1px);
            box-shadow: 0 6px 0 #0f172a, 0 10px 18px rgba(0, 0, 0, 0.45);
        }
        .arcade-btn:active:not(:disabled) {
            transform: translateY(4px);
            box-shadow: 0 1px 0 #0f172a, 0 2px 4px rgba(0, 0, 0, 0.4);
        }

        .btn-jump {
            background: linear-gradient(180deg, #10b981 0%, #059669 100%);
            border: 1px solid #34d399;
            box-shadow: 0 5px 0 #064e3b, 0 8px 16px rgba(16, 185, 129, 0.3);
        }
        .btn-jump:active:not(:disabled) {
            transform: translateY(4px);
            box-shadow: 0 1px 0 #064e3b;
        }

        .btn-sprint {
            background: linear-gradient(180deg, #f59e0b 0%, #d97706 100%);
            border: 1px solid #fbbf24;
            box-shadow: 0 5px 0 #78350f, 0 8px 16px rgba(245, 158, 11, 0.3);
        }
        .btn-sprint:active:not(:disabled) {
            transform: translateY(4px);
            box-shadow: 0 1px 0 #78350f;
        }

        .btn-duck {
            background: linear-gradient(180deg, #3b82f6 0%, #2563eb 100%);
            border: 1px solid #60a5fa;
            box-shadow: 0 5px 0 #1e3a8a, 0 8px 16px rgba(59, 130, 246, 0.3);
        }
        .btn-duck:active:not(:disabled) {
            transform: translateY(4px);
            box-shadow: 0 1px 0 #1e3a8a;
        }

        /* Floating HUD Glass Pill */
        .hud-pill {
            background: rgba(15, 23, 42, 0.72);
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 255, 255, 0.14);
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.pointer-events-none{pointer-events:none}.absolute{position:absolute}.inset-0{inset:0px}.left-3{left:0.75rem}.right-3{right:0.75rem}.top-3{top:0.75rem}.z-20{z-index:20}.my-auto{margin-top:auto;margin-bottom:auto}.mb-1{margin-bottom:0.25rem}.mb-2{margin-bottom:0.5rem}.mb-3{margin-bottom:0.75rem}.mb-5{margin-bottom:1.25rem}.mr-1{margin-right:0.25rem}.mt-3{margin-top:0.75rem}.mt-4{margin-top:1rem}.flex{display:flex}.hidden{display:none}.h-10{height:2.5rem}.h-16{height:4rem}.h-2\.5{height:0.625rem}.h-6{height:1.5rem}.h-9{height:2.25rem}.h-full{height:100%}.w-10{width:2.5rem}.w-16{width:4rem}.w-24{width:6rem}.w-6{width:1.5rem}.w-9{width:2.25rem}.w-full{width:100%}.max-w-3xl{max-width:48rem}.max-w-5xl{max-width:64rem}.max-w-md{max-width:28rem}.max-w-sm{max-width:24rem}.cursor-pointer{cursor:pointer}.grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.flex-col{flex-direction:column}.flex-wrap{flex-wrap:wrap}.items-start{align-items:flex-start}.items-end{align-items:flex-end}.items-center{align-items:center}.justify-end{justify-content:flex-end}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-1{gap:0.25rem}.gap-1\.5{gap:0.375rem}.gap-2{gap:0.5rem}.gap-2\.5{gap:0.625rem}.gap-3{gap:0.75rem}.overflow-hidden{overflow:hidden}.rounded{border-radius:0.25rem}.rounded-2xl{border-radius:1rem}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-xl{border-radius:0.75rem}.border{border-width:1px}.border-2{border-width:2px}.border-amber-200\/40{border-color:rgb(253 230 138 / 0.4)}.border-amber-300\/40{border-color:rgb(252 211 77 / 0.4)}.border-emerald-400\/50{border-color:rgb(52 211 153 / 0.5)}.border-slate-600{--tw-border-opacity:1;border-color:rgb(71 85 105 / var(--tw-border-opacity, 1))}.border-slate-700{--tw-border-opacity:1;border-color:rgb(51 65 85 / var(--tw-border-opacity, 1))}.border-transparent{border-color:transparent}.border-white{--tw-border-opacity:1;border-color:rgb(255 255 255 / var(--tw-border-opacity, 1))}.bg-\[\#1e293b\]{--tw-bg-opacity:1;background-color:rgb(30 41 59 / var(--tw-bg-opacity, 1))}.bg-\[\#8B4513\]{--tw-bg-opacity:1;background-color:rgb(139 69 19 / var(--tw-bg-opacity, 1))}.bg-\[\#d97706\]{--tw-bg-opacity:1;background-color:rgb(217 119 6 / var(--tw-bg-opacity, 1))}.bg-\[\#f1f5f9\]{--tw-bg-opacity:1;background-color:rgb(241 245 249 / var(--tw-bg-opacity, 1))}.bg-emerald-600{--tw-bg-opacity:1;background-color:rgb(5 150 105 / var(--tw-bg-opacity, 1))}.bg-emerald-950\/70{background-color:rgb(2 44 34 / 0.7)}.bg-slate-800{--tw-bg-opacity:1;background-color:rgb(30 41 59 / var(--tw-bg-opacity, 1))}.bg-slate-800\/90{background-color:rgb(30 41 59 / 0.9)}.bg-slate-900\/90{background-color:rgb(15 23 42 / 0.9)}.bg-slate-950\/65{background-color:rgb(2 6 23 / 0.65)}.bg-gradient-to-br{background-image:linear-gradient(to bottom right, var(--tw-gradient-stops))}.bg-gradient-to-r{background-image:linear-gradient(to right, var(--tw-gradient-stops))}.from-amber-400{--tw-gradient-from:#fbbf24 var(--tw-gradient-from-position);--tw-gradient-to:rgb(251 191 36 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-amber-500{--tw-gradient-from:#f59e0b var(--tw-gradient-from-position);--tw-gradient-to:rgb(245 158 11 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.to-emerald-400{--tw-gradient-to:#34d399 var(--tw-gradient-to-position)}.to-orange-600{--tw-gradient-to:#ea580c var(--tw-gradient-to-position)}.to-orange-700{--tw-gradient-to:#c2410c var(--tw-gradient-to-position)}.p-3{padding:0.75rem}.p-3\.5{padding:0.875rem}.p-5{padding:1.25rem}.px-1\.5{padding-left:0.375rem;padding-right:0.375rem}.px-2\.5{padding-left:0.625rem;padding-right:0.625rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.px-8{padding-left:2rem;padding-right:2rem}.px-9{padding-left:2.25rem;padding-right:2.25rem}.py-0\.5{padding-top:0.125rem;padding-bottom:0.125rem}.py-1{padding-top:0.25rem;padding-bottom:0.25rem}.py-1\.5{padding-top:0.375rem;padding-bottom:0.375rem}.py-3\.5{padding-top:0.875rem;padding-bottom:0.875rem}.py-4{padding-top:1rem;padding-bottom:1rem}.text-center{text-align:center}.text-right{text-align:right}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-\[10px\]{font-size:10px}.text-\[11px\]{font-size:11px}.text-base{font-size:1rem;line-height:1.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-bold{font-weight:700}.font-semibold{font-weight:600}.uppercase{text-transform:uppercase}.leading-none{line-height:1}.leading-tight{line-height:1.25}.tracking-wide{letter-spacing:0.025em}.tracking-wider{letter-spacing:0.05em}.text-amber-300{--tw-text-opacity:1;color:rgb(252 211 77 / var(--tw-text-opacity, 1))}.text-amber-400{--tw-text-opacity:1;color:rgb(251 191 36 / var(--tw-text-opacity, 1))}.text-emerald-300{--tw-text-opacity:1;color:rgb(110 231 183 / var(--tw-text-opacity, 1))}.text-emerald-400{--tw-text-opacity:1;color:rgb(52 211 153 / var(--tw-text-opacity, 1))}.text-slate-200{--tw-text-opacity:1;color:rgb(226 232 240 / var(--tw-text-opacity, 1))}.text-slate-300{--tw-text-opacity:1;color:rgb(203 213 225 / var(--tw-text-opacity, 1))}.text-slate-400{--tw-text-opacity:1;color:rgb(148 163 184 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.text-yellow-300{--tw-text-opacity:1;color:rgb(253 224 71 / var(--tw-text-opacity, 1))}.opacity-75{opacity:0.75}.shadow{--tw-shadow:0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 1px 3px 0 var(--tw-shadow-color), 0 1px 2px -1px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-xl{--tw-shadow:0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 20px 25px -5px var(--tw-shadow-color), 0 8px 10px -6px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.drop-shadow{--tw-drop-shadow:drop-shadow(0 1px 2px rgb(0 0 0 / 0.1)) drop-shadow(0 1px 1px rgb(0 0 0 / 0.06));filter:var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow)}.backdrop-blur-sm{--tw-backdrop-blur:blur(4px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition{transition-property:color, background-color, border-color, fill, stroke, opacity, box-shadow, transform, filter, -webkit-text-decoration-color, -webkit-backdrop-filter;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter, -webkit-text-decoration-color, -webkit-backdrop-filter;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-all{transition-property:all;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-75{transition-duration:75ms}.hover\:bg-emerald-500:hover{--tw-bg-opacity:1;background-color:rgb(16 185 129 / var(--tw-bg-opacity, 1))}.hover\:text-white:hover{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.hover\:opacity-100:hover{opacity:1}@media (min-width: 640px){.sm\:block{display:block}.sm\:inline{display:inline}.sm\:w-32{width:8rem}.sm\:gap-5{gap:1.25rem}.sm\:p-5{padding:1.25rem}.sm\:px-12{padding-left:3rem;padding-right:3rem}.sm\:px-8{padding-left:2rem;padding-right:2rem}.sm\:text-2xl{font-size:1.5rem;line-height:2rem}.sm\:text-4xl{font-size:2.25rem;line-height:2.5rem}.sm\:text-base{font-size:1rem;line-height:1.5rem}.sm\:text-lg{font-size:1.125rem;line-height:1.75rem}.sm\:text-sm{font-size:0.875rem;line-height:1.25rem}.sm\:text-xl{font-size:1.25rem;line-height:1.75rem}}</style></head>
<body class="flex flex-col items-center justify-between p-3 sm:p-5">

    <!-- Top Header Bar -->
    <header class="w-full max-w-5xl flex flex-wrap items-center justify-between gap-3 mb-2">
        <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-amber-500 to-orange-700 flex items-center justify-center shadow-lg border border-amber-300/40">
                <i class="fas fa-horse text-white text-xl"></i>
            </div>
            <div>
                <h1 class="font-game text-xl sm:text-2xl font-bold tracking-wide text-white">Derby Dash</h1>
                <p class="text-xs text-slate-400 hidden sm:block">Show Jumping • Stamina Gallop • Golden Horseshoes</p>
            </div>
        </div>

        <!-- Coat Selector & Audio Toggle -->
        <div class="flex items-center gap-2">
            <div class="bg-slate-800/90 px-2.5 py-1.5 rounded-xl border border-slate-700 flex items-center gap-1.5" title="Choose Horse Coat">
                <span class="text-xs text-slate-400 hidden sm:inline mr-1">Steed:</span>
                <button data-coat="bay" class="coat-btn w-6 h-6 rounded-full bg-[#8B4513] border-2 border-white shadow cursor-pointer" title="Chestnut Bay"></button>
                <button data-coat="white" class="coat-btn w-6 h-6 rounded-full bg-[#f1f5f9] border-2 border-transparent opacity-75 hover:opacity-100 shadow cursor-pointer" title="Royal White"></button>
                <button data-coat="black" class="coat-btn w-6 h-6 rounded-full bg-[#1e293b] border-2 border-transparent opacity-75 hover:opacity-100 shadow cursor-pointer" title="Midnight Stallion"></button>
                <button data-coat="palomino" class="coat-btn w-6 h-6 rounded-full bg-[#d97706] border-2 border-transparent opacity-75 hover:opacity-100 shadow cursor-pointer" title="Golden Palomino"></button>
            </div>

            <button id="soundToggleBtn" title="Toggle Sound" class="w-9 h-9 rounded-xl bg-slate-800 border border-slate-700 text-slate-200 hover:text-white flex items-center justify-center transition cursor-pointer">
                <i id="soundIcon" class="fas fa-volume-up"></i>
            </button>

            <button id="downloadGameBtn" title="Download Game File" class="px-3 h-9 rounded-xl bg-emerald-600 hover:bg-emerald-500 border border-emerald-400/50 text-white text-xs font-semibold flex items-center gap-1.5 shadow transition cursor-pointer">
                <i class="fas fa-download"></i> <span>Download</span>
            </button>
        </div>
    </header>

    <!-- Main Game Canvas Stage -->
    <main class="my-auto flex flex-col items-center">
        <div class="game-frame" id="gameContainer">
            <canvas id="gameCanvas" width="1200" height="675"></canvas>

            <!-- Top-Left & Top-Right Overlay HUD inside Canvas Frame -->
            <div class="absolute top-3 left-3 right-3 flex items-start justify-between pointer-events-none gap-2">
                <!-- Left: Distance, Score & Combo -->
                <div class="flex flex-wrap items-center gap-2">
                    <div class="hud-pill px-3 py-1.5 rounded-xl flex items-center gap-2">
                        <i class="fas fa-trophy text-amber-400 text-sm"></i>
                        <div>
                            <div class="text-[10px] uppercase tracking-wider text-slate-400 leading-none">Score</div>
                            <div id="hudScore" class="font-game text-base sm:text-lg font-bold text-white leading-tight">0</div>
                        </div>
                    </div>

                    <div class="hud-pill px-3 py-1.5 rounded-xl flex items-center gap-2">
                        <i class="fas fa-magnet text-yellow-300 text-sm"></i>
                        <div>
                            <div class="text-[10px] uppercase tracking-wider text-slate-400 leading-none">Shoes</div>
                            <div id="hudShoes" class="font-game text-base sm:text-lg font-bold text-yellow-300 leading-tight">0</div>
                        </div>
                    </div>

                    <div id="comboBadge" class="hidden hud-pill px-2.5 py-1.5 rounded-xl border-emerald-400/50 bg-emerald-950/70">
                        <span id="hudCombo" class="font-game text-xs sm:text-sm font-bold text-emerald-300">2x CLEAN JUMP!</span>
                    </div>
                </div>

                <!-- Right: Stamina Bar & High Score -->
                <div class="flex flex-col items-end gap-1.5">
                    <div class="hud-pill px-3 py-1.5 rounded-xl flex items-center gap-2.5">
                        <div class="text-right">
                            <div class="flex items-center justify-end gap-1 text-[10px] uppercase tracking-wider text-slate-300 leading-none mb-1">
                                <i class="fas fa-bolt text-amber-400"></i> Stamina
                            </div>
                            <div class="w-24 sm:w-32 h-2.5 bg-slate-800 rounded-full overflow-hidden border border-slate-600">
                                <div id="staminaBar" class="h-full bg-gradient-to-r from-amber-500 to-emerald-400 transition-all duration-75" style="width: 100%;"></div>
                            </div>
                        </div>
                    </div>

                    <div class="hud-pill px-2.5 py-1 rounded-lg text-[11px] text-slate-300">
                        Best: <span id="hudBest" class="font-bold text-amber-300">0</span>
                    </div>
                </div>
            </div>

            <!-- Start / Game Over Overlay Screen -->
            <div id="overlayScreen" class="absolute inset-0 bg-slate-950/65 backdrop-blur-sm flex flex-col items-center justify-center p-5 text-center z-20">
                <div id="overlayBadge" class="w-16 h-16 rounded-2xl bg-gradient-to-br from-amber-400 to-orange-600 flex items-center justify-center text-white text-3xl shadow-xl mb-3 border border-amber-200/40">
                    <i class="fas fa-horse-head"></i>
                </div>
                <h2 id="overlayTitle" class="font-game text-3xl sm:text-4xl font-bold text-white drop-shadow mb-1">Derby Dash</h2>
                <p id="overlaySubtitle" class="text-xs sm:text-sm text-slate-200 max-w-md mb-5">
                    Leap over fences &amp; water ditches, duck under low branches, collect golden horseshoes, and sprint for glory!
                </p>

                <!-- Final Run Stats (Shown on Game Over) -->
                <div id="finalStatsBox" class="hidden grid-cols-3 gap-3 bg-slate-900/90 border border-slate-700 rounded-2xl p-3.5 mb-5 w-full max-w-sm">
                    <div>
                        <div class="text-[10px] uppercase text-slate-400">Final Score</div>
                        <div id="finalScore" class="font-game text-xl font-bold text-white">0</div>
                    </div>
                    <div>
                        <div class="text-[10px] uppercase text-slate-400">Distance</div>
                        <div id="finalDist" class="font-game text-xl font-bold text-emerald-400">0m</div>
                    </div>
                    <div>
                        <div class="text-[10px] uppercase text-slate-400">Horseshoes</div>
                        <div id="finalShoes" class="font-game text-xl font-bold text-amber-400">0</div>
                    </div>
                </div>

                <button id="startRunBtn" class="btn-jump text-white font-game text-lg sm:text-xl font-bold px-8 py-3.5 rounded-2xl flex items-center gap-2.5 cursor-pointer">
                    <i class="fas fa-play"></i> <span id="startBtnLabel">Start Gallop</span>
                </button>

                <div class="mt-4 flex flex-wrap justify-center gap-3 text-[11px] text-slate-300">
                    <span><kbd class="bg-slate-800 px-1.5 py-0.5 rounded border border-slate-600">Space / ↑</kbd> Jump (Double Jump!)</span>
                    <span><kbd class="bg-slate-800 px-1.5 py-0.5 rounded border border-slate-600">↓ / S</kbd> Duck</span>
                    <span><kbd class="bg-slate-800 px-1.5 py-0.5 rounded border border-slate-600">→ / Shift</kbd> Sprint</span>
                </div>
            </div>
        </div>
    </main>

    <!-- Tactile Action Buttons Outside Canvas (Bottom Center with Generous Spacing) -->
    <footer class="w-full max-w-3xl flex flex-wrap items-center justify-center gap-3 sm:gap-5 mt-3 mb-1">
        <button id="btnDuck" class="btn-duck text-white font-game text-sm sm:text-base font-bold py-3.5 px-6 sm:px-8 rounded-2xl flex items-center gap-2 cursor-pointer">
            <i class="fas fa-arrow-down"></i> Duck
        </button>

        <button id="btnJump" class="btn-jump text-white font-game text-base sm:text-lg font-bold py-4 px-9 sm:px-12 rounded-2xl flex items-center gap-2.5 cursor-pointer">
            <i class="fas fa-arrow-up"></i> JUMP
        </button>

        <button id="btnSprint" class="btn-sprint text-white font-game text-sm sm:text-base font-bold py-3.5 px-6 sm:px-8 rounded-2xl flex items-center gap-2 cursor-pointer">
            <i class="fas fa-bolt"></i> Sprint
        </button>
    </footer>

    <script>
        /**
         * ============================================================================
         * DERBY DASH — PROCEDURAL HORSE RIDING & SHOW JUMPING ENGINE
         * Features:
         * - Articulated procedural horse & jockey animation (gallop cycle, rear-up jump,
         *   tuck/duck pose, flowing mane & tail physics, dust & sparkle particles)
         * - Multi-layer parallax countryside (rolling hills, snow-capped mountains,
         *   white picket rails, pine trees, clouds, and dynamic sun)
         * - Varied obstacles: Show Fences, Hedge Oxers, Water Ditches, and Overhead Banners
         * - Collectibles: Golden Horseshoes (+Score) & Fresh Apples (+Stamina)
         * - Responsive Canvas with DPI scaling, keyboard + touch/swipe + button controls
         * - Synthesized sound effects via Tone.js (hoofbeats, jump, coin chime, crash)
         * ============================================================================
         */

        // --- Coat Palettes ---
        const COAT_STYLES = {
            bay:      { body: '#8B4513', dark: '#5C2C06', mane: '#1c1917', sock: '#f8fafc' },
            white:    { body: '#f1f5f9', dark: '#cbd5e1', mane: '#94a3b8', sock: '#e2e8f0' },
            black:    { body: '#1e293b', dark: '#0f172a', mane: '#020617', sock: '#f8fafc' },
            palomino: { body: '#d97706', dark: '#b45309', mane: '#fef3c7', sock: '#fffbeb' }
        };

        // --- Sound Engine (Tone.js) ---
        class DerbyAudio {
            constructor() {
                this.enabled = true;
                this.ready = false;
                this.hoofSynth = null;
                this.fxSynth = null;
            }

            async init() {
                if (this.ready || typeof Tone === 'undefined') return;
                try {
                    await Tone.start();
                    this.hoofSynth = new Tone.MembraneSynth({
                        pitchDecay: 0.015,
                        octaves: 1.8,
                        envelope: { attack: 0.001, decay: 0.08, sustain: 0 }
                    }).toDestination();
                    this.hoofSynth.volume.value = -16;

                    this.fxSynth = new Tone.PolySynth(Tone.Synth, {
                        oscillator: { type: 'triangle' },
                        envelope: { attack: 0.005, decay: 0.15, sustain: 0.05, release: 0.2 }
                    }).toDestination();
                    this.fxSynth.volume.value = -10;
                    this.ready = true;
                } catch (e) {
                    console.warn('Audio init deferred:', e);
                }
            }

            play(type) {
                if (!this.enabled || !this.ready) return;
                try {
                    const now = Tone.now();
                    if (type === 'hoof') {
                        this.hoofSynth.triggerAttackRelease('G2', '32n', now);
                    } else if (type === 'jump') {
                        this.fxSynth.triggerAttackRelease(['C4', 'G4'], '16n', now);
                    } else if (type === 'doubleJump') {
                        this.fxSynth.triggerAttackRelease(['E4', 'B4'], '16n', now);
                    } else if (type === 'shoe') {
                        this.fxSynth.triggerAttackRelease(['B5', 'E6'], '16n', now);
                    } else if (type === 'apple') {
                        this.fxSynth.triggerAttackRelease(['F4', 'A4', 'C5'], '16n', now);
                    } else if (type === 'clear') {
                        this.fxSynth.triggerAttackRelease('G5', '32n', now);
                    } else if (type === 'crash') {
                        this.hoofSynth.triggerAttackRelease('C2', '4n', now);
                        this.fxSynth.triggerAttackRelease(['Eb3', 'A2'], '8n', now);
                    }
                } catch (e) {}
            }
        }

        const audio = new DerbyAudio();

        // --- Canvas & Game State Setup ---
        const canvas = document.getElementById('gameCanvas');
        const ctx = canvas.getContext('2d');
        const container = document.getElementById('gameContainer');

        let width = 800;
        let height = 450;
        let groundY = 365;

        function resizeCanvas() {
            const rect = container.getBoundingClientRect();
            const dpr = Math.min(window.devicePixelRatio || 1, 2);
            width = rect.width;
            height = rect.height;
            canvas.width = Math.floor(width * dpr);
            canvas.height = Math.floor(height * dpr);
            ctx.setTransform(dpr, 0, 0, dpr, 0, 0);
            groundY = height * 0.81;

            if (horse) {
                if (horse.y > groundY) horse.y = groundY;
            }
        }

        // --- Game State Object ---
        const state = {
            running: false,
            gameOver: false,
            score: 0,
            highScore: parseInt(localStorage.getItem('derbyDashBest') || '0', 10),
            distance: 0,
            shoes: 0,
            combo: 0,
            speed: 360,          // pixels per second
            baseSpeed: 360,
            maxSpeed: 760,
            sprinting: false,
            stamina: 100,        // 0 to 100
            coat: 'bay',
            time: 0,
            hoofTimer: 0,
            spawnTimer: 1.2,
            collectibleTimer: 0.8,
            shakeTime: 0,
            clouds: [],
            trees: [],
            particles: [],
            floatingTexts: [],
            obstacles: [],
            collectibles: []
        };

        // --- Player Horse Entity ---
        const horse = {
            x: 130,
            y: 365,
            vy: 0,
            width: 78,
            height: 62,
            jumpsRemaining: 2,
            isDucking: false,
            gallopPhase: 0,
            tilt: 0
        };

        // Initialize decorative clouds and background trees
        function initScenery() {
            state.clouds = Array.from({ length: 6 }, (_, i) => ({
                x: (i * 220) + Math.random() * 100,
                y: 35 + Math.random() * 95,
                scale: 0.7 + Math.random() * 0.6,
                speed: 18 + Math.random() * 15
            }));

            state.trees = Array.from({ length: 8 }, (_, i) => ({
                x: i * 165 + Math.random() * 60,
                scale: 0.75 + Math.random() * 0.5,
                type: i % 2
            }));
        }

        // --- Player Actions ---
        function triggerJump() {
            audio.init();
            if (!state.running) {
                if (!state.gameOver) startGame();
                return;
            }

            if (horse.jumpsRemaining > 0) {
                horse.isDucking = false;
                const isFirst = horse.jumpsRemaining === 2;
                horse.vy = isFirst ? -590 : -510;
                horse.jumpsRemaining--;
                audio.play(isFirst ? 'jump' : 'doubleJump');

                // Spawn burst of turf particles
                const burstColor = isFirst ? '#86efac' : '#fde047';
                for (let i = 0; i < 10; i++) {
                    state.particles.push({
                        x: horse.x - 10 + (Math.random() - 0.5) * 30,
                        y: horse.y,
                        vx: -80 - Math.random() * 140,
                        vy: -40 - Math.random() * 120,
                        size: 3 + Math.random() * 4,
                        color: burstColor,
                        life: 0.45
                    });
                }
            }
        }

        function setDuck(active) {
            audio.init();
            if (!state.running) return;
            horse.isDucking = active;
            // Fast-drop if ducking mid-air
            if (active && horse.y < groundY) {
                horse.vy = Math.max(horse.vy, 520);
            }
        }

        function setSprint(active) {
            audio.init();
            if (!state.running) return;
            state.sprinting = active && state.stamina > 5;
        }

        // --- Spawning Obstacles & Collectibles ---
        function spawnObstacle() {
            const types = ['fence', 'oxer', 'water', 'banner'];
            // Introduce overhead banners after 150m distance
            const pool = state.distance < 120 ? ['fence', 'water'] : types;
            const type = pool[Math.floor(Math.random() * pool.length)];

            let obs = {
                type,
                x: width + 60,
                cleared: false
            };

            if (type === 'fence') {
                obs.w = 32;
                obs.h = 54 + Math.random() * 14;
                obs.y = groundY - obs.h;
            } else if (type === 'oxer') {
                // Wide double-rail jump
                obs.w = 64;
                obs.h = 48;
                obs.y = groundY - obs.h;
            } else if (type === 'water') {
                // Wide ground water ditch
                obs.w = 95;
                obs.h = 14;
                obs.y = groundY - 4;
            } else if (type === 'banner') {
                // Overhead crossbeam: safe when ducking, lethal if standing/jumping high
                obs.w = 46;
                obs.h = 38;
                obs.y = groundY - 86; // Clearance of 48px underneath for ducking horse
            }

            state.obstacles.push(obs);
        }

        function spawnCollectible() {
            const isApple = state.stamina < 65 && Math.random() < 0.35;
            const arcHeight = Math.random() < 0.5 ? 36 : 115; // Ground level or jump arc
            state.collectibles.push({
                type: isApple ? 'apple' : 'shoe',
                x: width + 50,
                y: groundY - arcHeight,
                radius: 15,
                bobOffset: Math.random() * Math.PI * 2,
                collected: false
            });
        }

        function addFloatingText(x, y, text, color) {
            state.floatingTexts.push({
                x,
                y,
                text,
                color,
                life: 0.9
            });
        }

        // --- Game Lifecycle ---
        function startGame() {
            audio.init();
            state.running = true;
            state.gameOver = false;
            state.score = 0;
            state.distance = 0;
            state.shoes = 0;
            state.combo = 0;
            state.speed = state.baseSpeed;
            state.sprinting = false;
            state.stamina = 100;
            state.spawnTimer = 1.1;
            state.collectibleTimer = 0.7;
            state.obstacles = [];
            state.collectibles = [];
            state.particles = [];
            state.floatingTexts = [];

            horse.x = Math.min(140, width * 0.2);
            horse.y = groundY;
            horse.vy = 0;
            horse.jumpsRemaining = 2;
            horse.isDucking = false;

            document.getElementById('overlayScreen').classList.add('hidden');
            updateHUD();
        }

        function endGame() {
            state.running = false;
            state.gameOver = true;
            state.shakeTime = 0.35;
            audio.play('crash');

            const finalPoints = Math.floor(state.score);
            if (finalPoints > state.highScore) {
                state.highScore = finalPoints;
                localStorage.setItem('derbyDashBest', String(state.highScore));
            }

            document.getElementById('overlayBadge').innerHTML = '<i class="fas fa-flag-checkered"></i>';
            document.getElementById('overlayTitle').textContent = 'Course Knockdown!';
            document.getElementById('overlaySubtitle').textContent = 'Your steed clipped an obstacle. Ready for another run?';
            document.getElementById('finalStatsBox').classList.remove('hidden');
            document.getElementById('finalStatsBox').classList.add('grid');
            document.getElementById('finalScore').textContent = finalPoints;
            document.getElementById('finalDist').textContent = `${Math.floor(state.distance)}m`;
            document.getElementById('finalShoes').textContent = state.shoes;
            document.getElementById('startBtnLabel').textContent = 'Ride Again';
            document.getElementById('overlayScreen').classList.remove('hidden');
            updateHUD();
        }

        // --- Physics & Simulation Step ---
        function update(dt) {
            state.time += dt;
            if (state.shakeTime > 0) state.shakeTime = Math.max(0, state.shakeTime - dt);

            // Drift clouds even on title screen
            state.clouds.forEach(c => {
                c.x -= c.speed * dt;
                if (c.x < -140) c.x = width + 120;
            });

            if (!state.running) return;

            // Progressive speed scaling + Sprint boost
            state.baseSpeed = Math.min(620, 360 + state.distance * 0.32);
            if (state.sprinting && state.stamina > 0) {
                state.speed = state.baseSpeed * 1.38;
                state.stamina = Math.max(0, state.stamina - 28 * dt);
                if (state.stamina <= 0) state.sprinting = false;
            } else {
                state.speed += (state.baseSpeed - state.speed) * 6 * dt;
                state.stamina = Math.min(100, state.stamina + 11 * dt);
            }

            // Advance distance & score
            const distDelta = (state.speed * dt) / 28;
            state.distance += distDelta;
            state.score += distDelta * (state.sprinting ? 2.5 : 1.5);

            // Parallax trees
            state.trees.forEach(t => {
                t.x -= state.speed * 0.45 * dt;
                if (t.x < -100) t.x = width + 80 + Math.random() * 80;
            });

            // Horse vertical physics
            const gravity = 1650;
            if (horse.y < groundY || horse.vy < 0) {
                horse.vy += gravity * dt;
                horse.y += horse.vy * dt;
                if (horse.y >= groundY) {
                    horse.y = groundY;
                    horse.vy = 0;
                    horse.jumpsRemaining = 2;
                }
            }

            // Gallop animation & rhythmic hoofbeat sound
            if (horse.y >= groundY) {
                const gallopFreq = (state.speed / 360) * 13;
                horse.gallopPhase += gallopFreq * dt;
                state.hoofTimer -= dt * (state.speed / 360);
                if (state.hoofTimer <= 0) {
                    audio.play('hoof');
                    state.hoofTimer = 0.24;
                    // Kick up turf dust
                    state.particles.push({
                        x: horse.x - 24,
                        y: groundY - 2,
                        vx: -state.speed * 0.35 - Math.random() * 40,
                        vy: -15 - Math.random() * 35,
                        size: 2.5 + Math.random() * 2.5,
                        color: state.sprinting ? '#fbbf24' : '#a3e635',
                        life: 0.35
                    });
                }
            }

            // Spawn Obstacles
            state.spawnTimer -= dt;
            if (state.spawnTimer <= 0) {
                spawnObstacle();
                const minGap = Math.max(0.88, 1.85 - state.distance * 0.0012);
                state.spawnTimer = minGap + Math.random() * 0.65;
            }

            // Spawn Collectibles
            state.collectibleTimer -= dt;
            if (state.collectibleTimer <= 0) {
                spawnCollectible();
                state.collectibleTimer = 1.1 + Math.random() * 1.1;
            }

            // Horse Hitbox (forgiving inner bounding box for fair arcade feel)
            const hHeight = horse.isDucking ? 34 : 54;
            const hBox = {
                left: horse.x - 24,
                right: horse.x + 26,
                top: horse.y - hHeight,
                bottom: horse.y - 4
            };

            // Update & Check Obstacles
            for (let i = state.obstacles.length - 1; i >= 0; i--) {
                const obs = state.obstacles[i];
                obs.x -= state.speed * dt;

                // Clean jump / duck award when passing obstacle
                if (!obs.cleared && obs.x + obs.w < hBox.left) {
                    obs.cleared = true;
                    state.combo++;
                    const bonus = 25 * Math.min(state.combo, 5);
                    state.score += bonus;
                    audio.play('clear');
                    addFloatingText(horse.x, horse.y - 75, `+${bonus}`, '#34d399');
                }

                // Collision Check
                const oBox = {
                    left: obs.x + 4,
                    right: obs.x + obs.w - 4,
                    top: obs.y + 4,
                    bottom: obs.y + obs.h
                };

                const overlaps =
                    hBox.right > oBox.left &&
                    hBox.left < oBox.right &&
                    hBox.bottom > oBox.top &&
                    hBox.top < oBox.bottom;

                if (overlaps) {
                    endGame();
                    return;
                }

                if (obs.x + obs.w < -80) {
                    state.obstacles.splice(i, 1);
                }
            }

            // Update & Check Collectibles
            for (let i = state.collectibles.length - 1; i >= 0; i--) {
                const col = state.collectibles[i];
                col.x -= state.speed * dt;
                const bobY = col.y + Math.sin(state.time * 5 + col.bobOffset) * 6;

                const dx = horse.x - col.x;
                const dy = (horse.y - 30) - bobY;
                if (Math.hypot(dx, dy) < 42) {
                    if (col.type === 'shoe') {
                        state.shoes++;
                        state.score += 50;
                        audio.play('shoe');
                        addFloatingText(col.x, bobY - 15, '+50', '#fde047');
                    } else {
                        state.stamina = Math.min(100, state.stamina + 35);
                        state.score += 30;
                        audio.play('apple');
                        addFloatingText(col.x, bobY - 15, '+STAMINA', '#4ade80');
                    }

                    for (let p = 0; p < 8; p++) {
                        state.particles.push({
                            x: col.x,
                            y: bobY,
                            vx: (Math.random() - 0.5) * 180,
                            vy: (Math.random() - 0.5) * 180,
                            size: 3.5,
                            color: col.type === 'shoe' ? '#fde047' : '#f87171',
                            life: 0.4
                        });
                    }
                    state.collectibles.splice(i, 1);
                    continue;
                }

                if (col.x < -50) state.collectibles.splice(i, 1);
            }

            // Update Particles & Floating Score Popups
            for (let i = state.particles.length - 1; i >= 0; i--) {
                const p = state.particles[i];
                p.x += p.vx * dt;
                p.y += p.vy * dt;
                p.life -= dt;
                if (p.life <= 0) state.particles.splice(i, 1);
            }

            for (let i = state.floatingTexts.length - 1; i >= 0; i--) {
                const ft = state.floatingTexts[i];
                ft.y -= 45 * dt;
                ft.life -= dt;
                if (ft.life <= 0) state.floatingTexts.splice(i, 1);
            }

            updateHUD();
        }

        function updateHUD() {
            document.getElementById('hudScore').textContent = Math.floor(state.score);
            document.getElementById('hudShoes').textContent = state.shoes;
            document.getElementById('hudBest').textContent = state.highScore;
            document.getElementById('staminaBar').style.width = `${Math.round(state.stamina)}%`;

            const comboBadge = document.getElementById('comboBadge');
            if (state.combo >= 2 && state.running) {
                comboBadge.classList.remove('hidden');
                document.getElementById('hudCombo').textContent = `${Math.min(state.combo, 5)}x STREAK!`;
            } else {
                comboBadge.classList.add('hidden');
            }
        }

        // ============================================================================
        // RENDERING PIPELINE (ARTICULATED HORSE, PARALLAX ARENA & OBSTACLES)
        // ============================================================================

        function drawBackground() {
            // Sky Gradient
            const skyGrad = ctx.createLinearGradient(0, 0, 0, groundY);
            skyGrad.addColorStop(0, '#0284c7');
            skyGrad.addColorStop(0.6, '#38bdf8');
            skyGrad.addColorStop(1, '#bae6fd');
            ctx.fillStyle = skyGrad;
            ctx.fillRect(0, 0, width, groundY);

            // Warm Sun
            ctx.save();
            ctx.fillStyle = 'rgba(254, 240, 138, 0.35)';
            ctx.beginPath();
            ctx.arc(width * 0.82, height * 0.18, 46, 0, Math.PI * 2);
            ctx.fill();
            ctx.fillStyle = '#fef08a';
            ctx.beginPath();
            ctx.arc(width * 0.82, height * 0.18, 30, 0, Math.PI * 2);
            ctx.fill();
            ctx.restore();

            // Clouds
            ctx.fillStyle = 'rgba(255, 255, 255, 0.88)';
            state.clouds.forEach(c => {
                ctx.save();
                ctx.translate(c.x, c.y);
                ctx.scale(c.scale, c.scale);
                ctx.beginPath();
                ctx.arc(0, 0, 22, 0, Math.PI * 2);
                ctx.arc(20, -6, 26, 0, Math.PI * 2);
                ctx.arc(44, 0, 20, 0, Math.PI * 2);
                ctx.fill();
                ctx.restore();
            });

            // Distant Rolling Mountains
            ctx.fillStyle = '#64748b';
            ctx.beginPath();
            ctx.moveTo(0, groundY);
            for (let x = 0; x <= width + 100; x += 120) {
                const peakH = 95 + Math.sin(x * 0.008) * 35;
                ctx.lineTo(x, groundY - peakH);
            }
            ctx.lineTo(width, groundY);
            ctx.closePath();
            ctx.fill();

            // Midground Lush Hills
            ctx.fillStyle = '#22c55e';
            ctx.beginPath();
            ctx.moveTo(0, groundY);
            for (let x = 0; x <= width + 80; x += 80) {
                const hillH = 42 + Math.cos(x * 0.012 + state.distance * 0.02) * 16;
                ctx.lineTo(x, groundY - hillH);
            }
            ctx.lineTo(width, groundY);
            ctx.closePath();
            ctx.fill();

            // Background Pine Trees
            state.trees.forEach(t => {
                ctx.save();
                ctx.translate(t.x, groundY - 12);
                ctx.scale(t.scale, t.scale);
                ctx.fillStyle = '#78350f';
                ctx.fillRect(-4, -18, 8, 18);
                ctx.fillStyle = '#15803d';
                ctx.beginPath();
                ctx.moveTo(0, -58);
                ctx.lineTo(-20, -18);
                ctx.lineTo(20, -18);
                ctx.closePath();
                ctx.fill();
                ctx.restore();
            });

            // White Picket Track Fence
            const railSpacing = 56;
            const offset = (state.distance * 28) % railSpacing;
            ctx.fillStyle = '#f8fafc';
            ctx.fillRect(0, groundY - 24, width, 4);
            ctx.fillRect(0, groundY - 13, width, 4);
            for (let x = -offset; x < width + railSpacing; x += railSpacing) {
                ctx.fillRect(x, groundY - 30, 6, 30);
            }

            // Turf & Dirt Track Ground
            ctx.fillStyle = '#16a34a';
            ctx.fillRect(0, groundY, width, 14);
            const dirtGrad = ctx.createLinearGradient(0, groundY + 14, 0, height);
            dirtGrad.addColorStop(0, '#92400e');
            dirtGrad.addColorStop(1, '#451a03');
            ctx.fillStyle = dirtGrad;
            ctx.fillRect(0, groundY + 14, width, height - groundY - 14);
        }

        function drawHorseAndJockey() {
            const palette = COAT_STYLES[state.coat] || COAT_STYLES.bay;
            const isAirborne = horse.y < groundY - 2;
            const phase = horse.gallopPhase;

            ctx.save();
            ctx.translate(horse.x, horse.y);

            // Ground Shadow
            const heightAboveGround = Math.max(0, groundY - horse.y);
            const shadowScale = Math.max(0.35, 1 - heightAboveGround / 220);
            ctx.fillStyle = 'rgba(0, 0, 0, 0.28)';
            ctx.beginPath();
            ctx.ellipse(0, heightAboveGround + 4, 38 * shadowScale, 8 * shadowScale, 0, 0, Math.PI * 2);
            ctx.fill();

            // Dynamic Body Pitch (Tilt up on ascent, down on descent)
            let pitch = 0;
            if (isAirborne) {
                pitch = Math.max(-0.38, Math.min(0.35, horse.vy * 0.00055));
            } else if (horse.isDucking) {
                pitch = 0.12;
            } else {
                pitch = Math.sin(phase * 2) * 0.04;
            }
            ctx.rotate(pitch);

            const bodyY = horse.isDucking ? -22 : -32;

            // Helper to draw an articulated leg
            const drawLeg = (hipX, hipY, angle1, angle2, color) => {
                ctx.save();
                ctx.translate(hipX, hipY);
                ctx.rotate(angle1);
                ctx.fillStyle = color;
                ctx.beginPath();
                ctx.roundRect(-4, 0, 8, 16, 4);
                ctx.fill();

                ctx.translate(0, 14);
                ctx.rotate(angle2);
                ctx.beginPath();
                ctx.roundRect(-3.5, 0, 7, 15, 3);
                ctx.fill();

                // White sock & dark hoof
                ctx.fillStyle = palette.sock;
                ctx.fillRect(-3.5, 10, 7, 5);
                ctx.fillStyle = '#0f172a';
                ctx.fillRect(-4, 14, 8, 4);
                ctx.restore();
            };

            // Back-side legs (darker shade for depth)
            const legSwing1 = isAirborne ? -0.65 : Math.sin(phase) * 0.65;
            const legSwing2 = isAirborne ? 0.75 : Math.cos(phase) * 0.65;
            drawLeg(-18, bodyY + 6, -legSwing1, 0.35, palette.dark);
            drawLeg(18, bodyY + 6, -legSwing2, -0.35, palette.dark);

            // Flowing Tail
            ctx.save();
            ctx.translate(-26, bodyY - 4);
            const tailWave = Math.sin(state.time * 12) * 0.22;
            ctx.rotate(tailWave);
            ctx.fillStyle = palette.mane;
            ctx.beginPath();
            ctx.moveTo(0, 0);
            ctx.quadraticCurveTo(-22, 4, -26, 22);
            ctx.quadraticCurveTo(-12, 18, -4, 6);
            ctx.closePath();
            ctx.fill();
            ctx.restore();

            // Horse Torso
            ctx.fillStyle = palette.body;
            ctx.beginPath();
            ctx.ellipse(0, bodyY, 28, horse.isDucking ? 12 : 14, 0, 0, Math.PI * 2);
            ctx.fill();

            // Foreground Legs
            drawLeg(-16, bodyY + 6, legSwing1, 0.3, palette.body);
            drawLeg(20, bodyY + 6, legSwing2, -0.4, palette.body);

            // Neck & Head (Lowers forward when ducking)
            ctx.save();
            ctx.translate(20, bodyY - 4);
            ctx.rotate(horse.isDucking ? 0.75 : -0.35 + Math.sin(phase * 2) * 0.05);

            // Neck
            ctx.fillStyle = palette.body;
            ctx.beginPath();
            ctx.roundRect(-7, -24, 15, 28, 7);
            ctx.fill();

            // Mane along neck
            ctx.fillStyle = palette.mane;
            ctx.beginPath();
            ctx.roundRect(-10, -23, 5, 22, 3);
            ctx.fill();

            // Head & Snout
            ctx.translate(4, -24);
            ctx.rotate(0.55);
            ctx.fillStyle = palette.body;
            ctx.beginPath();
            ctx.ellipse(6, 0, 13, 7.5, 0, 0, Math.PI * 2);
            ctx.fill();

            // Ear
            ctx.beginPath();
            ctx.moveTo(-2, -5);
            ctx.lineTo(-5, -13);
            ctx.lineTo(2, -6);
            ctx.closePath();
            ctx.fill();

            // Eye & Bridle
            ctx.fillStyle = '#0f172a';
            ctx.beginPath();
            ctx.arc(4, -2, 2, 0, Math.PI * 2);
            ctx.fill();
            ctx.strokeStyle = '#dc2626';
            ctx.lineWidth = 2;
            ctx.beginPath();
            ctx.moveTo(13, -5);
            ctx.lineTo(13, 5);
            ctx.stroke();
            ctx.restore();

            // Saddle & Jockey Rider
            ctx.fillStyle = '#78350f';
            ctx.beginPath();
            ctx.ellipse(-2, bodyY - 12, 11, 5, 0, 0, Math.PI * 2);
            ctx.fill();

            // Jockey Torso & Helmet (Crouches forward when ducking or sprinting)
            ctx.save();
            ctx.translate(-2, bodyY - 13);
            ctx.rotate(horse.isDucking ? 0.95 : (state.sprinting ? 0.45 : 0.2));

            // Jockey Silk Jacket
            ctx.fillStyle = '#ef4444';
            ctx.beginPath();
            ctx.roundRect(-6, -18, 12, 18, 5);
            ctx.fill();

            // Jockey Helmet
            ctx.fillStyle = '#1e293b';
            ctx.beginPath();
            ctx.arc(1, -22, 6.5, 0, Math.PI * 2);
            ctx.fill();
            // Helmet Visor
            ctx.fillRect(2, -23, 8, 2.5);
            ctx.restore();

            ctx.restore();
        }

        function drawObstaclesAndCollectibles() {
            // Obstacles
            state.obstacles.forEach(obs => {
                if (obs.type === 'fence' || obs.type === 'oxer') {
                    // Striped Show-Jumping Rails & Standards
                    const stripes = 4;
                    const barHeight = 8;
                    for (let row = 0; row < 2; row++) {
                        const railY = obs.y + row * 18;
                        const segW = obs.w / stripes;
                        for (let s = 0; s < stripes; s++) {
                            ctx.fillStyle = s % 2 === 0 ? '#ef4444' : '#ffffff';
                            ctx.fillRect(obs.x + s * segW, railY, segW, barHeight);
                        }
                    }
                    // Side posts
                    ctx.fillStyle = '#f8fafc';
                    ctx.fillRect(obs.x - 3, obs.y - 6, 6, obs.h + 6);
                    ctx.fillRect(obs.x + obs.w - 3, obs.y - 6, 6, obs.h + 6);
                } else if (obs.type === 'water') {
                    // Water Jump Ditch
                    ctx.fillStyle = '#0284c7';
                    ctx.beginPath();
                    ctx.roundRect(obs.x, obs.y, obs.w, obs.h, 6);
                    ctx.fill();
                    ctx.fillStyle = '#7dd3fc';
                    ctx.fillRect(obs.x + 8, obs.y + 3, obs.w - 16, 3);
                } else if (obs.type === 'banner') {
                    // Overhead Cross-Banner (Requires Ducking!)
                    ctx.fillStyle = '#b91c1c';
                    ctx.beginPath();
                    ctx.roundRect(obs.x, obs.y, obs.w, obs.h, 6);
                    ctx.fill();
                    ctx.strokeStyle = '#fde047';
                    ctx.lineWidth = 2;
                    ctx.strokeRect(obs.x + 3, obs.y + 3, obs.w - 6, obs.h - 6);

                    // Down-arrow indicator on banner
                    ctx.fillStyle = '#fef08a';
                    ctx.font = 'bold 11px Inter, sans-serif';
                    ctx.textAlign = 'center';
                    ctx.fillText('DUCK', obs.x + obs.w / 2, obs.y + 23);
                }
            });

            // Collectibles (Golden Horseshoes & Stamina Apples)
            state.collectibles.forEach(col => {
                const bobY = col.y + Math.sin(state.time * 5 + col.bobOffset) * 6;
                ctx.save();
                ctx.translate(col.x, bobY);

                if (col.type === 'shoe') {
                    // Glowing Golden Horseshoe
                    ctx.strokeStyle = '#facc15';
                    ctx.lineWidth = 5;
                    ctx.lineCap = 'round';
                    ctx.beginPath();
                    ctx.arc(0, 0, 10, Math.PI * 0.2, Math.PI * 1.8, false);
                    ctx.stroke();
                } else {
                    // Crisp Red Apple (+Stamina)
                    ctx.fillStyle = '#ef4444';
                    ctx.beginPath();
                    ctx.arc(0, 2, 11, 0, Math.PI * 2);
                    ctx.fill();
                    ctx.fillStyle = '#22c55e';
                    ctx.beginPath();
                    ctx.ellipse(4, -10, 6, 3, -0.4, 0, Math.PI * 2);
                    ctx.fill();
                }
                ctx.restore();
            });

            // Particles
            state.particles.forEach(p => {
                ctx.globalAlpha = Math.max(0, p.life * 2);
                ctx.fillStyle = p.color;
                ctx.beginPath();
                ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
                ctx.fill();
            });
            ctx.globalAlpha = 1;

            // Floating Bonus Texts
            state.floatingTexts.forEach(ft => {
                ctx.globalAlpha = Math.min(1, ft.life * 1.5);
                ctx.fillStyle = ft.color;
                ctx.font = 'bold 15px Fredoka, sans-serif';
                ctx.textAlign = 'center';
                ctx.fillText(ft.text, ft.x, ft.y);
            });
            ctx.globalAlpha = 1;
        }

        function render() {
            ctx.save();
            if (state.shakeTime > 0) {
                const mag = state.shakeTime * 18;
                ctx.translate((Math.random() - 0.5) * mag, (Math.random() - 0.5) * mag);
            }

            drawBackground();
            drawObstaclesAndCollectibles();
            drawHorseAndJockey();

            ctx.restore();
        }

        // --- Main Animation Loop ---
        let lastTimestamp = 0;
        function gameLoop(timestamp) {
            if (!lastTimestamp) lastTimestamp = timestamp;
            const dt = Math.min(0.05, (timestamp - lastTimestamp) / 1000);
            lastTimestamp = timestamp;

            update(dt);
            render();
            requestAnimationFrame(gameLoop);
        }

        // ============================================================================
        // INPUT BINDINGS (KEYBOARD, TOUCH SWIPES, AND ARCADE BUTTONS)
        // ============================================================================

        window.addEventListener('keydown', (e) => {
            if (['Space', 'ArrowUp', 'ArrowDown', 'ArrowRight'].includes(e.code)) {
                e.preventDefault();
            }
            if (e.code === 'Space' || e.code === 'ArrowUp' || e.code === 'KeyW') {
                triggerJump();
            } else if (e.code === 'ArrowDown' || e.code === 'KeyS') {
                setDuck(true);
            } else if (e.code === 'ArrowRight' || e.code === 'ShiftLeft' || e.code === 'ShiftRight') {
                setSprint(true);
            }
        });

        window.addEventListener('keyup', (e) => {
            if (e.code === 'ArrowDown' || e.code === 'KeyS') {
                setDuck(false);
            } else if (e.code === 'ArrowRight' || e.code === 'ShiftLeft' || e.code === 'ShiftRight') {
                setSprint(false);
            }
        });

        // Touch Swipe / Tap Gestures on Canvas
        let touchStartY = 0;
        canvas.addEventListener('touchstart', (e) => {
            touchStartY = e.touches[0].clientY;
        }, { passive: true });

        canvas.addEventListener('touchmove', (e) => {
            const dy = e.touches[0].clientY - touchStartY;
            if (dy > 28) setDuck(true);
        }, { passive: true });

        canvas.addEventListener('touchend', (e) => {
            const dy = e.changedTouches[0].clientY - touchStartY;
            if (horse.isDucking) {
                setDuck(false);
            } else if (dy < 20) {
                triggerJump();
            }
        });

        // Tactile Arcade Buttons (Mouse & Touch)
        const btnJump = document.getElementById('btnJump');
        const btnDuck = document.getElementById('btnDuck');
        const btnSprint = document.getElementById('btnSprint');

        btnJump.addEventListener('pointerdown', (e) => { e.preventDefault(); triggerJump(); });

        btnDuck.addEventListener('pointerdown', (e) => { e.preventDefault(); setDuck(true); });
        btnDuck.addEventListener('pointerup', () => setDuck(false));
        btnDuck.addEventListener('pointerleave', () => setDuck(false));

        btnSprint.addEventListener('pointerdown', (e) => { e.preventDefault(); setSprint(true); });
        btnSprint.addEventListener('pointerup', () => setSprint(false));
        btnSprint.addEventListener('pointerleave', () => setSprint(false));

        document.getElementById('startRunBtn').addEventListener('click', startGame);

        // Coat Color Selector
        document.querySelectorAll('.coat-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                state.coat = btn.dataset.coat;
                document.querySelectorAll('.coat-btn').forEach(b => {
                    b.classList.remove('border-white', 'opacity-100');
                    b.classList.add('border-transparent', 'opacity-75');
                });
                btn.classList.remove('border-transparent', 'opacity-75');
                btn.classList.add('border-white', 'opacity-100');
            });
        });

        // Audio Toggle
        document.getElementById('soundToggleBtn').addEventListener('click', () => {
            audio.enabled = !audio.enabled;
            document.getElementById('soundIcon').className = audio.enabled
                ? 'fas fa-volume-up'
                : 'fas fa-volume-mute text-rose-400';
        });

        // One-Click Self-Contained HTML Download
        document.getElementById('downloadGameBtn').addEventListener('click', () => {
            const htmlContent = '<!DOCTYPE html>\n' + document.documentElement.outerHTML;
            const blob = new Blob([htmlContent], { type: 'text/html;charset=utf-8' });
            const url = URL.createObjectURL(blob);
            const link = document.createElement('a');
            link.href = url;
            link.download = 'derby-dash-horse-game.html';
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
            URL.revokeObjectURL(url);
        });

        window.addEventListener('resize', resizeCanvas);

        // Start on Window Load
        window.onload = function () {
            resizeCanvas();
            initScenery();
            horse.y = groundY;
            updateHUD();
            requestAnimationFrame(gameLoop);
        };
    </script>

</body></html>
