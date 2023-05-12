# Rural Credit 

The Central Bank of Brazil makes rural credit data available from the SICOR Database. More details about the types of credit and other information can be accessed through the link <https://www.bcb.gov.br/estabilidadefinanceira/creditorural>

In this work, we accessed data from two tables with data on rural properties and loan amounts received (SICOR_PROPRIEDADES & SICOR_LIBERACAO_RECURSOS)

The model and data dictionary are available at the link below: <https://www.bcb.gov.br/estabilidadefinanceira/creditorural?modalAberto=tabelas_sicor>

The Brazilian Forestry Service makes spatial data with the delimitation of rural properties available. Public access offers only the manual download municipality by municipality through the link <https://www.car.gov.br/publico/municipios/downloads>

The Legal Amazon comprises 9 Brazilian states. However, in this study only, the shapefiles of rural properties in Rondônia, Mato Grosso and Pará were downloaded.

Every year the National Institute for Space Research (INPE) maps out the increase in deforestation based on satellite images. Information about the PRODES Project can be accessed through the link [http://www.obt.inpe.br/OBT/assuntos/programas/amazonia/prodes](#0){.uri}. The methodology used since 1988 has been improved over the years, and today, all policies to combat deforestation and the Brazilian NDC use PRODES data as a basis.

The analysis starts by identifying which rural properties suffered any deforestation after August 2008. It is essential to understand that the PRODES data always comprise 12 months from August of one year to July of the following year.

Another critical concept to be understood is the expiration of the punitive intention. According to law 9605, in general, deforestation that has been committed five years or more ago can no longer receive a fine. In addition, law 12651 determines that deforestation committed without authorization after July 22, 2008, is not eligible for regularization.

For these reasons, only data from PRODES after July 2008 are being used in this analysis. Furthermore, the SICOR data began in 2013, which allows us to verify if, after 2013, any properties that received rural credit had committed deforestation in the previous five years.
