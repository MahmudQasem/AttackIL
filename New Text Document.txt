<?php
$r = new HttpRequest('https://1e492660cbf23ce4ba61a5fb128445b9.m.pipedream.net', HttpRequest::METH_GET);
$r->send();
echo $r->getResponseCode();
?>
