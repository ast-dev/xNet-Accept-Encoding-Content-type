# xNet-Accept-Encoding-Content-type

xNet library - recompiled with Accept-Encoding and Content-type headers.
Now you can easy add this headers without any dancing.

Example:

                        req["Accept"] = "application/json";
                        req["User-Agent"] = "%USERAGENT%";
                        req["Content-Type"] = "application/json";
                        req["Accept-Encoding"] = "gzip";
                        req.KeepAlive = true;

                        response = req.Get("https://pentagon.com").ToString();
