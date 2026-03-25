noinst_PROGRAMS = sign1 sign2 sign3 sign4 \
                  verify1 verify2 verify3 verify4 verify-saml \
                  encrypt1 encrypt2 encrypt3

AM_CFLAGS = -I $(top_srcdir)/include -DXMLSEC_CRYPTO_DYNAMIC_LOADING $(XMLSEC_CORE_CFLAGS) $(LIBXML_CFLAGS) $(LIBXSLT_CFLAGS)
LDADD = ../src/libxmlsec1.la $(LIBXML_LIBS) $(LIBXSLT_LIBS)
