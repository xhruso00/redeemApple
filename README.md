# redeemApple
Short tutorial on how to redeem multiple codes from Apple

Digi (MY)
curl -H 'Host: redeem.apple.com' -H 'Accept: */*' -H 'User-Agent: Mozilla/5.0 (iPhone; CPU iPhone OS 14_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/14.0.1 Mobile/15E148 Safari/604.1' -H 'Accept-Language: en-us' -H 'Referer: http://redeem.apple.com/digi' --compressed 'http://redeem.apple.com/campaigns/5fa096d4f8afb00015047966/call_to_actions/5fa096d4f8afb00015047967/fetch_code?at=missing-sales-rep&captcha=__VAR_CAPTCHA__'

Telstra (AUS)
curl -H 'Host: redeem.apple.com' -H 'If-None-Match: W/"032155477e7dba81349ae4f434676159"' -H 'Accept: */*' -H 'User-Agent: Mozilla/5.0 (iPhone; CPU iPhone OS 14_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/14.0.1 Mobile/15E148 Safari/604.1' -H 'Accept-Language: en-us' -H 'Referer: http://redeem.apple.com/digi' --compressed 'http://redeem.apple.com/campaigns/5f7d05cf13878000073b6da8/call_to_actions/5f7d05d013878000073b6da9/fetch_code?at=missing-sales-rep&captcha=__VAR_CAPTCHA__'
