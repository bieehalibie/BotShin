 // Failed
 -echo $response->getHTTPStatus . ' ' . $response->getRawBody();
 +echo $response->getHTTPStatus() . ' ' . $response->getRawBody();
