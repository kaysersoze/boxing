
lib_LIBRARIES = libunboxing.a
libunboxing_a_CFLAGS = \
	-I${top_srcdir}/inc \
	-I${top_srcdir}/thirdparty/glib \
	-I${top_srcdir}/thirdparty/ldpc \
    -I${top_srcdir}/thirdparty/bch \
	-I${top_srcdir}/./thirdparty/reedsolomon \
    -I${top_srcdir}/src/unboxer \
    -I${top_srcdir}/src/frame \
	-I${top_srcdir}/../boxingdata/inc \
	-D RAND_FILE="\"./randfile\""

libunboxing_a_SOURCES = \
    ../thirdparty/reedsolomon/rs.c \
    ../thirdparty/reedsolomon/galois_field.c \
    ../thirdparty/ldpc/alloc.c \
    ../thirdparty/ldpc/blockio.c \
    ../thirdparty/ldpc/channel.c \
    ../thirdparty/ldpc/check.c \
    ../thirdparty/ldpc/dec.c \
    ../thirdparty/ldpc/distrib.c \
    ../thirdparty/ldpc/enc.c \
    ../thirdparty/ldpc/intio.c \
    ../thirdparty/ldpc/mod2convert.c \
    ../thirdparty/ldpc/mod2dense.c \
    ../thirdparty/ldpc/mod2sparse.c \
    ../thirdparty/ldpc/open.c \
    ../thirdparty/ldpc/rand.c \
    ../thirdparty/ldpc/rcode.c \
    ../thirdparty/glib/gnode.c \
    ../thirdparty/glib/ghash.c \
    ../thirdparty/glib/g_variant.c \
    ../thirdparty/glib/gtree.c \
    ../thirdparty/glib/glist.c \
    ../thirdparty/glib/gvector.c \
    ../thirdparty/glib/gutils.c \
    ../thirdparty/bch/bch_test.c \
    ../thirdparty/bch/bch.c \
    log.c \
    unboxer.c \
    string.c \
    matrix.c \
    math/bitutils.c \
    math/dsp.c \
    math/math.c \
    codecs/codecbase.c \
    codecs/packetheader.c \
    codecs/reedsolomon.c \
    codecs/interleaving.c \
    codecs/bchcodec.c \
    codecs/ftfinterleaving.c \
    codecs/crc32.c \
    codecs/codecdispatcher.c \
    codecs/2dpam.c \
    codecs/cipher.c \
    codecs/ldpccodec.c \
    codecs/syncpointinserter.c \
    codecs/symbolconverter.c \
    codecs/modulator.c \
    codecs/crc64.c \
    metadata.c \
    stats.c \
    utils.c \
    image8.c \
    unboxer/unboxerv1.c \
    unboxer/unboxerv1.h \
    unboxer/horizontalmeasures.c \
    unboxer/datapoints.c \
    unboxer/histogramutils.c \
    unboxer/frametrackerutil.c \
    unboxer/sampleutil.c \
    unboxer/filter.c \
    unboxer/frameutil.c \
    unboxer/cornermark.c \
    unboxer/syncpoints.c \
    base/math_crc64.c \
    base/math_crc32.c \
    platform/memory.c \
    platform/platform.c \
    frame/trackergpf_1.c \
    frame/bilinearsampler.c \
    frame/sampler.c \
    frame/areasampler.c \
    frame/bicubicsampler.c \
    frame/trackergpf.c \
    frame/2polinomialsampler.c \
    graphics/contentcontainer.c \
    graphics/genericframefactory.c \
    graphics/border.c \
    graphics/referencepoint.c \
    graphics/image8paintdevice.c \
    graphics/component.c \
    graphics/metadatabar.c \
    graphics/calibrationbar.c \
    graphics/painter.c \
    graphics/referencebar.c \
    graphics/genericframe.c \
    graphics/label.c \
    graphics/genericframegpf_1.c \
    config.c \
    globals.c

nobase_include_HEADERS = \
    ../inc/boxing/filter.h \
    ../inc/boxing/globals.h \
    ../inc/boxing/utils.h \
    ../inc/boxing/config.h \
    ../inc/boxing/stats.h \
    ../inc/boxing/math/crc32.h \
    ../inc/boxing/math/crc64.h \
    ../inc/boxing/math/bitutils.h \
    ../inc/boxing/math/dsp.h \
    ../inc/boxing/math/math.h \
    ../inc/boxing/codecs/packetheader.h \
    ../inc/boxing/codecs/crc32.h \
    ../inc/boxing/codecs/bchcodec.h \
    ../inc/boxing/codecs/codecdispatcher.h \
    ../inc/boxing/codecs/ftfinterleaving.h \
    ../inc/boxing/codecs/codecbase.h \
    ../inc/boxing/codecs/crc64.h \
    ../inc/boxing/codecs/2dpam.h \
    ../inc/boxing/codecs/codec_cb.h \
    ../inc/boxing/codecs/modulator.h \
    ../inc/boxing/codecs/syncpointinserter.h \
    ../inc/boxing/codecs/interleaving.h \
    ../inc/boxing/codecs/symbolconverter.h \
    ../inc/boxing/codecs/cipher.h \
    ../inc/boxing/codecs/reedsolomon.h \
    ../inc/boxing/codecs/ldpccodec.h \
    ../inc/boxing/log.h \
    ../inc/boxing/unboxer.h \
    ../inc/boxing/bool.h \
    ../inc/boxing/matrix.h \
    ../inc/boxing/unboxer/abstractframeutil.h \
    ../inc/boxing/unboxer/cornermark.h \
    ../inc/boxing/unboxer/sampleutil.h \
    ../inc/boxing/unboxer/syncpoints.h \
    ../inc/boxing/unboxer/histogramutils.h \
    ../inc/boxing/unboxer/frametrackerutil.h \
    ../inc/boxing/unboxer/sampler.h \
    ../inc/boxing/platform/platform.h \
    ../inc/boxing/platform/types.h \
    ../inc/boxing/platform/memory.h \
    ../inc/boxing/image8.h \
    ../inc/boxing/string.h \
    ../inc/boxing/frame/trackercbgpf_1.h \
    ../inc/boxing/frame/tracker.h \
    ../inc/boxing/frame/trackergpf.h \
    ../inc/boxing/frame/trackergpf_1.h \
    ../inc/boxing/graphics/painter.h \
    ../inc/boxing/graphics/component.h \
    ../inc/boxing/graphics/image8paintdevice.h \
    ../inc/boxing/graphics/referencepoint.h \
    ../inc/boxing/graphics/genericframefactory.h \
    ../inc/boxing/graphics/genericframe.h \
    ../inc/boxing/graphics/referencebar.h \
    ../inc/boxing/graphics/label.h \
    ../inc/boxing/graphics/paintdevice.h \
    ../inc/boxing/graphics/border.h \
    ../inc/boxing/graphics/metadatabar.h \
    ../inc/boxing/graphics/calibrationbar.h \
    ../inc/boxing/graphics/contentcontainer.h \
    ../inc/boxing/graphics/genericframegpf_1.h \
    ../inc/boxing/metadata.h \
    ../thirdparty/reedsolomon/rs.h \
    ../thirdparty/reedsolomon/galois_field.h \
    ../thirdparty/ldpc/alloc.h \
    ../thirdparty/ldpc/blockio.h \
    ../thirdparty/ldpc/channel.h \
    ../thirdparty/ldpc/check.h \
    ../thirdparty/ldpc/dec.h \
    ../thirdparty/ldpc/distrib.h \
    ../thirdparty/ldpc/enc.h \
    ../thirdparty/ldpc/intio.h \
    ../thirdparty/ldpc/mod2convert.h \
    ../thirdparty/ldpc/mod2dense.h \
    ../thirdparty/ldpc/mod2sparse.h \
    ../thirdparty/ldpc/open.h \
    ../thirdparty/ldpc/rand.h \
    ../thirdparty/ldpc/rcode.h \
    ../thirdparty/glib/glib.h \
    ../thirdparty/glib/ghash.h \
    ../thirdparty/glib/gvector.h \
    ../thirdparty/glib/glibconfig.h \
    ../thirdparty/glib/gtree.h \
    ../thirdparty/glib/gmacros.h \
    ../thirdparty/glib/gnode.h \
    ../thirdparty/glib/glist.h \
    ../thirdparty/glib/g_variant.h \
    ../thirdparty/glib/gutils.h \
    ../thirdparty/glib/gversionmacros.h \
    ../thirdparty/glib/gtypes.h \
    ../thirdparty/bch/bch.h \
    unboxer/horizontalmeasures.h \
    unboxer/frameutil.h \
    unboxer/datapoints.h \
    base/config.h \
    frame/bilinearsampler.h \
    frame/bicubicsampler.h \
    frame/areasampler.h \
    frame/2polinomialsampler.h 
