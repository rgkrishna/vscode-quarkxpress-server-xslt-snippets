# QuarkXPress Server XSLT Snippets README

XSLT snippets for QuarkXPress Server.
A useful set of XSLT snippets to increase coding XSLTs for QuarkXPress Server. 
Primarily intended to help developers working on XSLTs for Smart Content to QuarkXPress Server modifier XMLs.

## Snippets

| Prefix      | Description |
| ----------- | ----------------------------------- |
| cm        | `<!-- $1 -->`  |
| var       | `<xsl:variable name="$1" select="$2"/>` |
| val       | `<xsl:value-of select="$1"/>` |
| choose    | `<xsl:choose><xsl:when test="$1">$2</xsl:when><xsl:otherwise>$3</xsl:otherwise></xsl:choose>` |
| when      | `<xsl:when test="$1">$2</xsl:when>` |
| otherwise | `<xsl:otherwise>$1</xsl:otherwise>` |
| if        | `<xsl:if test="$1">$2</xsl:if>` |
| temp      | `<xsl:template match="$1">$2</xsl:template>` |
| param     | `<xsl:param name="$1" select="$2"/>` |
| with      | `<xsl:with-param name="$1" select="$2"/>` |
| attribute | `<xsl:attribute name="$1" select="$2"/>` |
| text      | `<xsl:text>$1</xsl:text>` |
| apply     | `<xsl:apply-templates select="$1"/>` |
| sty       | `<xsl:stylesheet xmlns:xsl="http://www.w3.org/1999/XSL/Transform" xmlns:xs="http://www.w3.org/2001/XMLSchema" xpath-default-namespace="http://quark.com/smartcontent/4.0" exclude-result-prefixes="xs" version="2.0"> $1 </xsl:stylesheet>` |



**Happy XSLT coding!!!**