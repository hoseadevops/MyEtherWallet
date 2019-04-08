<template>
  <div class="crypto-icons">
    <img :src="selectedCoin" />
  </div>
</template>

<script>
import $pac from '@/assets/images/networks/circle/$pac.svg';
import toGive from '@/assets/images/networks/circle/2give.svg';
import abt from '@/assets/images/networks/circle/abt.svg';
import act from '@/assets/images/networks/circle/act.svg';
import actn from '@/assets/images/networks/circle/actn.svg';
import ada from '@/assets/images/networks/circle/ada.svg';
import add from '@/assets/images/networks/circle/add.svg';
import adx from '@/assets/images/networks/circle/adx.svg';
import ae from '@/assets/images/networks/circle/ae.svg';
import aeon from '@/assets/images/networks/circle/aeon.svg';
import aeur from '@/assets/images/networks/circle/aeur.svg';
import agi from '@/assets/images/networks/circle/agi.svg';
import agrs from '@/assets/images/networks/circle/agrs.svg';
import aion from '@/assets/images/networks/circle/aion.svg';
import amb from '@/assets/images/networks/circle/amb.svg';
import amp from '@/assets/images/networks/circle/amp.svg';
import ant from '@/assets/images/networks/circle/ant.svg';
import apex from '@/assets/images/networks/circle/apex.svg';
import appc from '@/assets/images/networks/circle/appc.svg';
import ardr from '@/assets/images/networks/circle/ardr.svg';
import arg from '@/assets/images/networks/circle/arg.svg';
import ark from '@/assets/images/networks/circle/ark.svg';
import arn from '@/assets/images/networks/circle/arn.svg';
import ary from '@/assets/images/networks/circle/ary.svg';
import ast from '@/assets/images/networks/circle/ast.svg';
import atm from '@/assets/images/networks/circle/atm.svg';
import audr from '@/assets/images/networks/circle/audr.svg';
import auto from '@/assets/images/networks/circle/auto.svg';
import aywa from '@/assets/images/networks/circle/aywa.svg';
import bab from '@/assets/images/networks/circle/bab.svg';
import bat from '@/assets/images/networks/circle/bat.svg';
import bay from '@/assets/images/networks/circle/bay.svg';
import bcbc from '@/assets/images/networks/circle/bcbc.svg';
import bcc from '@/assets/images/networks/circle/bcc.svg';
import bcd from '@/assets/images/networks/circle/bcd.svg';
import bch from '@/assets/images/networks/circle/bch.svg';
import bcio from '@/assets/images/networks/circle/bcio.svg';
import bcn from '@/assets/images/networks/circle/bcn.svg';
import bco from '@/assets/images/networks/circle/bco.svg';
import bcpt from '@/assets/images/networks/circle/bcpt.svg';
import bdl from '@/assets/images/networks/circle/bdl.svg';
import beam from '@/assets/images/networks/circle/beam.svg';
import bela from '@/assets/images/networks/circle/bela.svg';
import bix from '@/assets/images/networks/circle/bix.svg';
import blcn from '@/assets/images/networks/circle/blcn.svg';
import blk from '@/assets/images/networks/circle/blk.svg';
import block from '@/assets/images/networks/circle/block.svg';
import blz from '@/assets/images/networks/circle/blz.svg';
import bnb from '@/assets/images/networks/circle/bnb.svg';
import bnt from '@/assets/images/networks/circle/bnt.svg';
import bnty from '@/assets/images/networks/circle/bnty.svg';
import booty from '@/assets/images/networks/circle/booty.svg';
import bos from '@/assets/images/networks/circle/bos.svg';
import bpt from '@/assets/images/networks/circle/bpt.svg';
import bq from '@/assets/images/networks/circle/bq.svg';
import brd from '@/assets/images/networks/circle/brd.svg';
import bsd from '@/assets/images/networks/circle/bsd.svg';
import bsv from '@/assets/images/networks/circle/bsv.svg';
import btc from '@/assets/images/networks/circle/btc.svg';
import btcd from '@/assets/images/networks/circle/btcd.svg';
import btch from '@/assets/images/networks/circle/btch.svg';
import btcp from '@/assets/images/networks/circle/btcp.svg';
import btcz from '@/assets/images/networks/circle/btcz.svg';
import btdx from '@/assets/images/networks/circle/btdx.svg';
import btg from '@/assets/images/networks/circle/btg.svg';
import btm from '@/assets/images/networks/circle/btm.svg';
import bts from '@/assets/images/networks/circle/bts.svg';
import btt from '@/assets/images/networks/circle/btt.svg';
import btx from '@/assets/images/networks/circle/btx.svg';
import burst from '@/assets/images/networks/circle/burst.svg';
import call from '@/assets/images/networks/circle/call.svg';
import cc from '@/assets/images/networks/circle/cc.svg';
import cdn from '@/assets/images/networks/circle/cdn.svg';
import cdt from '@/assets/images/networks/circle/cdt.svg';
import cenz from '@/assets/images/networks/circle/cenz.svg';
import chain from '@/assets/images/networks/circle/chain.svg';
import chat from '@/assets/images/networks/circle/chat.svg';
import chips from '@/assets/images/networks/circle/chips.svg';
import cix from '@/assets/images/networks/circle/cix.svg';
import clam from '@/assets/images/networks/circle/clam.svg';
import cloak from '@/assets/images/networks/circle/cloak.svg';
import cmm from '@/assets/images/networks/circle/cmm.svg';
import cmt from '@/assets/images/networks/circle/cmt.svg';
import cnd from '@/assets/images/networks/circle/cnd.svg';
import cnx from '@/assets/images/networks/circle/cnx.svg';
import cny from '@/assets/images/networks/circle/cny.svg';
import cob from '@/assets/images/networks/circle/cob.svg';
import colx from '@/assets/images/networks/circle/colx.svg';
import coqui from '@/assets/images/networks/circle/coqui.svg';
import cred from '@/assets/images/networks/circle/cred.svg';
import crpt from '@/assets/images/networks/circle/crpt.svg';
import crw from '@/assets/images/networks/circle/crw.svg';
import cs from '@/assets/images/networks/circle/cs.svg';
import ctr from '@/assets/images/networks/circle/ctr.svg';
import ctxc from '@/assets/images/networks/circle/ctxc.svg';
import cvc from '@/assets/images/networks/circle/cvc.svg';
import dai from '@/assets/images/networks/circle/dai.svg';
import dash from '@/assets/images/networks/circle/dash.svg';
import dat from '@/assets/images/networks/circle/dat.svg';
import data from '@/assets/images/networks/circle/data.svg';
import dbc from '@/assets/images/networks/circle/dbc.svg';
import dcn from '@/assets/images/networks/circle/dcn.svg';
import dcr from '@/assets/images/networks/circle/dcr.svg';
import deez from '@/assets/images/networks/circle/deez.svg';
import dent from '@/assets/images/networks/circle/dent.svg';
import dew from '@/assets/images/networks/circle/dew.svg';
import dgb from '@/assets/images/networks/circle/dgb.svg';
import dgd from '@/assets/images/networks/circle/dgd.svg';
import dlt from '@/assets/images/networks/circle/dlt.svg';
import dnr from '@/assets/images/networks/circle/dnr.svg';
import dnt from '@/assets/images/networks/circle/dnt.svg';
import dock from '@/assets/images/networks/circle/dock.svg';
import doge from '@/assets/images/networks/circle/doge.svg';
import drgn from '@/assets/images/networks/circle/drgn.svg';
import drop from '@/assets/images/networks/circle/drop.svg';
import dta from '@/assets/images/networks/circle/dta.svg';
import dth from '@/assets/images/networks/circle/dth.svg';
import dtr from '@/assets/images/networks/circle/dtr.svg';
import ebst from '@/assets/images/networks/circle/ebst.svg';
import eca from '@/assets/images/networks/circle/eca.svg';
import edg from '@/assets/images/networks/circle/edg.svg';
import edo from '@/assets/images/networks/circle/edo.svg';
import edoge from '@/assets/images/networks/circle/edoge.svg';
import ela from '@/assets/images/networks/circle/ela.svg';
import elf from '@/assets/images/networks/circle/elf.svg';
import elix from '@/assets/images/networks/circle/elix.svg';
import ella from '@/assets/images/networks/circle/ella.svg';
import emc from '@/assets/images/networks/circle/emc.svg';
import emc2 from '@/assets/images/networks/circle/emc2.svg';
import eng from '@/assets/images/networks/circle/eng.svg';
import enj from '@/assets/images/networks/circle/enj.svg';
import entrp from '@/assets/images/networks/circle/entrp.svg';
import eon from '@/assets/images/networks/circle/eon.svg';
import eop from '@/assets/images/networks/circle/eop.svg';
import eos from '@/assets/images/networks/circle/eos.svg';
import eqli from '@/assets/images/networks/circle/eqli.svg';
import equa from '@/assets/images/networks/circle/equa.svg';
import etc from '@/assets/images/networks/circle/etc.svg';
import eth from '@/assets/images/networks/circle/eth.svg';
import ethos from '@/assets/images/networks/circle/ethos.svg';
import etn from '@/assets/images/networks/circle/etn.svg';
import etp from '@/assets/images/networks/circle/etp.svg';
import eur from '@/assets/images/networks/circle/eur.svg';
import evx from '@/assets/images/networks/circle/evx.svg';
import exmo from '@/assets/images/networks/circle/exmo.svg';
import exp from '@/assets/images/networks/circle/exp.svg';
import fair from '@/assets/images/networks/circle/fair.svg';
import fct from '@/assets/images/networks/circle/fct.svg';
import fil from '@/assets/images/networks/circle/fil.svg';
import fjc from '@/assets/images/networks/circle/fjc.svg';
import fldc from '@/assets/images/networks/circle/fldc.svg';
import flo from '@/assets/images/networks/circle/flo.svg';
import fsn from '@/assets/images/networks/circle/fsn.svg';
import ftc from '@/assets/images/networks/circle/ftc.svg';
import fuel from '@/assets/images/networks/circle/fuel.svg';
import fun from '@/assets/images/networks/circle/fun.svg';
import game from '@/assets/images/networks/circle/game.svg';
import gas from '@/assets/images/networks/circle/gas.svg';
import gbp from '@/assets/images/networks/circle/gbp.svg';
import gbx from '@/assets/images/networks/circle/gbx.svg';
import gbyte from '@/assets/images/networks/circle/gbyte.svg';
import generic from '@/assets/images/networks/circle/generic.svg';
import gin from '@/assets/images/networks/circle/gin.svg';
import glxt from '@/assets/images/networks/circle/glxt.svg';
import gmr from '@/assets/images/networks/circle/gmr.svg';
import gno from '@/assets/images/networks/circle/gno.svg';
import gnt from '@/assets/images/networks/circle/gnt.svg';
import gold from '@/assets/images/networks/circle/gold.svg';
import grc from '@/assets/images/networks/circle/grc.svg';
import grin from '@/assets/images/networks/circle/grin.svg';
import grs from '@/assets/images/networks/circle/grs.svg';
import gsc from '@/assets/images/networks/circle/gsc.svg';
import gto from '@/assets/images/networks/circle/gto.svg';
import gup from '@/assets/images/networks/circle/gup.svg';
import gusd from '@/assets/images/networks/circle/gusd.svg';
import gvt from '@/assets/images/networks/circle/gvt.svg';
import gxs from '@/assets/images/networks/circle/gxs.svg';
import gzr from '@/assets/images/networks/circle/gzr.svg';
import hight from '@/assets/images/networks/circle/hight.svg';
import hodl from '@/assets/images/networks/circle/hodl.svg';
import hot from '@/assets/images/networks/circle/hot.svg';
import hpb from '@/assets/images/networks/circle/hpb.svg';
import hsr from '@/assets/images/networks/circle/hsr.svg';
import ht from '@/assets/images/networks/circle/ht.svg';
import html from '@/assets/images/networks/circle/html.svg';
import huc from '@/assets/images/networks/circle/huc.svg';
import hush from '@/assets/images/networks/circle/hush.svg';
import icn from '@/assets/images/networks/circle/icn.svg';
import icx from '@/assets/images/networks/circle/icx.svg';
import ignis from '@/assets/images/networks/circle/ignis.svg';
import ilk from '@/assets/images/networks/circle/ilk.svg';
import ink from '@/assets/images/networks/circle/ink.svg';
import ins from '@/assets/images/networks/circle/ins.svg';
import ion from '@/assets/images/networks/circle/ion.svg';
import iop from '@/assets/images/networks/circle/iop.svg';
import iost from '@/assets/images/networks/circle/iost.svg';
import iotx from '@/assets/images/networks/circle/iotx.svg';
import iq from '@/assets/images/networks/circle/iq.svg';
import itc from '@/assets/images/networks/circle/itc.svg';
import jnt from '@/assets/images/networks/circle/jnt.svg';
import jpy from '@/assets/images/networks/circle/jpy.svg';
import kcs from '@/assets/images/networks/circle/kcs.svg';
import kin from '@/assets/images/networks/circle/kin.svg';
import kmd from '@/assets/images/networks/circle/kmd.svg';
import knc from '@/assets/images/networks/circle/knc.svg';
import krb from '@/assets/images/networks/circle/krb.svg';
import lbc from '@/assets/images/networks/circle/lbc.svg';
import lend from '@/assets/images/networks/circle/lend.svg';
import link from '@/assets/images/networks/circle/link.svg';
import lkk from '@/assets/images/networks/circle/lkk.svg';
import loom from '@/assets/images/networks/circle/loom.svg';
import lpt from '@/assets/images/networks/circle/lpt.svg';
import lrc from '@/assets/images/networks/circle/lrc.svg';
import lsk from '@/assets/images/networks/circle/lsk.svg';
import ltc from '@/assets/images/networks/circle/ltc.svg';
import lun from '@/assets/images/networks/circle/lun.svg';
import maid from '@/assets/images/networks/circle/maid.svg';
import mana from '@/assets/images/networks/circle/mana.svg';
import mcap from '@/assets/images/networks/circle/mcap.svg';
import mco from '@/assets/images/networks/circle/mco.svg';
import mda from '@/assets/images/networks/circle/mda.svg';
import mds from '@/assets/images/networks/circle/mds.svg';
import med from '@/assets/images/networks/circle/med.svg';
import meetone from '@/assets/images/networks/circle/meetone.svg';
import miota from '@/assets/images/networks/circle/miota.svg';
import mith from '@/assets/images/networks/circle/mith.svg';
import mkr from '@/assets/images/networks/circle/mkr.svg';
import mln from '@/assets/images/networks/circle/mln.svg';
import mnx from '@/assets/images/networks/circle/mnx.svg';
import mnz from '@/assets/images/networks/circle/mnz.svg';
import moac from '@/assets/images/networks/circle/moac.svg';
import mod from '@/assets/images/networks/circle/mod.svg';
import mona from '@/assets/images/networks/circle/mona.svg';
import msr from '@/assets/images/networks/circle/msr.svg';
import mth from '@/assets/images/networks/circle/mth.svg';
import mtl from '@/assets/images/networks/circle/mtl.svg';
import music from '@/assets/images/networks/circle/music.svg';
import mzc from '@/assets/images/networks/circle/mzc.svg';
import nano from '@/assets/images/networks/circle/nano.svg';
import nas from '@/assets/images/networks/circle/nas.svg';
import nav from '@/assets/images/networks/circle/nav.svg';
import ncash from '@/assets/images/networks/circle/ncash.svg';
import ndz from '@/assets/images/networks/circle/ndz.svg';
import nebl from '@/assets/images/networks/circle/nebl.svg';
import neo from '@/assets/images/networks/circle/neo.svg';
import neos from '@/assets/images/networks/circle/neos.svg';
import neu from '@/assets/images/networks/circle/neu.svg';
import nexo from '@/assets/images/networks/circle/nexo.svg';
import ngc from '@/assets/images/networks/circle/ngc.svg';
import nio from '@/assets/images/networks/circle/nio.svg';
import nlc2 from '@/assets/images/networks/circle/nlc2.svg';
import nlg from '@/assets/images/networks/circle/nlg.svg';
import nmc from '@/assets/images/networks/circle/nmc.svg';
import npxs from '@/assets/images/networks/circle/npxs.svg';
import nuls from '@/assets/images/networks/circle/nuls.svg';
import nxs from '@/assets/images/networks/circle/nxs.svg';
import nxt from '@/assets/images/networks/circle/nxt.svg';
import oax from '@/assets/images/networks/circle/oax.svg';
import ok from '@/assets/images/networks/circle/ok.svg';
import omg from '@/assets/images/networks/circle/omg.svg';
import omni from '@/assets/images/networks/circle/omni.svg';
import ong from '@/assets/images/networks/circle/ong.svg';
import ont from '@/assets/images/networks/circle/ont.svg';
import oot from '@/assets/images/networks/circle/oot.svg';
import ost from '@/assets/images/networks/circle/ost.svg';
import ox from '@/assets/images/networks/circle/ox.svg';
import part from '@/assets/images/networks/circle/part.svg';
import pasc from '@/assets/images/networks/circle/pasc.svg';
import pasl from '@/assets/images/networks/circle/pasl.svg';
import pax from '@/assets/images/networks/circle/pax.svg';
import pay from '@/assets/images/networks/circle/pay.svg';
import payx from '@/assets/images/networks/circle/payx.svg';
import pink from '@/assets/images/networks/circle/pink.svg';
import pirl from '@/assets/images/networks/circle/pirl.svg';
import pivx from '@/assets/images/networks/circle/pivx.svg';
import plr from '@/assets/images/networks/circle/plr.svg';
import poa from '@/assets/images/networks/circle/poa.svg';
import poe from '@/assets/images/networks/circle/poe.svg';
import polis from '@/assets/images/networks/circle/polis.svg';
import poly from '@/assets/images/networks/circle/poly.svg';
import pot from '@/assets/images/networks/circle/pot.svg';
import powr from '@/assets/images/networks/circle/powr.svg';
import ppc from '@/assets/images/networks/circle/ppc.svg';
import ppp from '@/assets/images/networks/circle/ppp.svg';
import ppt from '@/assets/images/networks/circle/ppt.svg';
import pre from '@/assets/images/networks/circle/pre.svg';
import prl from '@/assets/images/networks/circle/prl.svg';
import pungo from '@/assets/images/networks/circle/pungo.svg';
import pura from '@/assets/images/networks/circle/pura.svg';
import qash from '@/assets/images/networks/circle/qash.svg';
import qiwi from '@/assets/images/networks/circle/qiwi.svg';
import qlc from '@/assets/images/networks/circle/qlc.svg';
import qrl from '@/assets/images/networks/circle/qrl.svg';
import qsp from '@/assets/images/networks/circle/qsp.svg';
import qtum from '@/assets/images/networks/circle/qtum.svg';
import r from '@/assets/images/networks/circle/r.svg';
import rads from '@/assets/images/networks/circle/rads.svg';
import rap from '@/assets/images/networks/circle/rap.svg';
import rcn from '@/assets/images/networks/circle/rcn.svg';
import rdd from '@/assets/images/networks/circle/rdd.svg';
import rdn from '@/assets/images/networks/circle/rdn.svg';
import rep from '@/assets/images/networks/circle/rep.svg';
import req from '@/assets/images/networks/circle/req.svg';
import rhoc from '@/assets/images/networks/circle/rhoc.svg';
import ric from '@/assets/images/networks/circle/ric.svg';
import rise from '@/assets/images/networks/circle/rise.svg';
import rlc from '@/assets/images/networks/circle/rlc.svg';
import rpx from '@/assets/images/networks/circle/rpx.svg';
import rub from '@/assets/images/networks/circle/rub.svg';
import rvn from '@/assets/images/networks/circle/rvn.svg';
import ryo from '@/assets/images/networks/circle/ryo.svg';
import safe from '@/assets/images/networks/circle/safe.svg';
import salt from '@/assets/images/networks/circle/salt.svg';
import san from '@/assets/images/networks/circle/san.svg';
import sbd from '@/assets/images/networks/circle/sbd.svg';
import sberbank from '@/assets/images/networks/circle/sberbank.svg';
import sc from '@/assets/images/networks/circle/sc.svg';
import shift from '@/assets/images/networks/circle/shift.svg';
import sib from '@/assets/images/networks/circle/sib.svg';
import sky from '@/assets/images/networks/circle/sky.svg';
import slr from '@/assets/images/networks/circle/slr.svg';
import sls from '@/assets/images/networks/circle/sls.svg';
import smart from '@/assets/images/networks/circle/smart.svg';
import sngls from '@/assets/images/networks/circle/sngls.svg';
import snm from '@/assets/images/networks/circle/snm.svg';
import snt from '@/assets/images/networks/circle/snt.svg';
import soc from '@/assets/images/networks/circle/soc.svg';
import spank from '@/assets/images/networks/circle/spank.svg';
import sphtx from '@/assets/images/networks/circle/sphtx.svg';
import srn from '@/assets/images/networks/circle/srn.svg';
import stak from '@/assets/images/networks/circle/stak.svg';
import start from '@/assets/images/networks/circle/start.svg';
import steem from '@/assets/images/networks/circle/steem.svg';
import storj from '@/assets/images/networks/circle/storj.svg';
import storm from '@/assets/images/networks/circle/storm.svg';
import stq from '@/assets/images/networks/circle/stq.svg';
import strat from '@/assets/images/networks/circle/strat.svg';
import sub from '@/assets/images/networks/circle/sub.svg';
import sumo from '@/assets/images/networks/circle/sumo.svg';
import sys from '@/assets/images/networks/circle/sys.svg';
import taas from '@/assets/images/networks/circle/taas.svg';
import tau from '@/assets/images/networks/circle/tau.svg';
import tbx from '@/assets/images/networks/circle/tbx.svg';
import tel from '@/assets/images/networks/circle/tel.svg';
import ten from '@/assets/images/networks/circle/ten.svg';
import tern from '@/assets/images/networks/circle/tern.svg';
import tghc from '@/assets/images/networks/circle/tghc.svg';
import theta from '@/assets/images/networks/circle/theta.svg';
import tix from '@/assets/images/networks/circle/tix.svg';
import tkn from '@/assets/images/networks/circle/tkn.svg';
import tks from '@/assets/images/networks/circle/tks.svg';
import tnb from '@/assets/images/networks/circle/tnb.svg';
import tnc from '@/assets/images/networks/circle/tnc.svg';
import tnt from '@/assets/images/networks/circle/tnt.svg';
import tomo from '@/assets/images/networks/circle/tomo.svg';
import tpay from '@/assets/images/networks/circle/tpay.svg';
import trig from '@/assets/images/networks/circle/trig.svg';
import trtl from '@/assets/images/networks/circle/trtl.svg';
import trx from '@/assets/images/networks/circle/trx.svg';
import tusd from '@/assets/images/networks/circle/tusd.svg';
import tzc from '@/assets/images/networks/circle/tzc.svg';
import ubq from '@/assets/images/networks/circle/ubq.svg';
import unity from '@/assets/images/networks/circle/unity.svg';
import usd from '@/assets/images/networks/circle/usd.svg';
import usdc from '@/assets/images/networks/circle/usdc.svg';
import usdt from '@/assets/images/networks/circle/usdt.svg';
import utk from '@/assets/images/networks/circle/utk.svg';
import veri from '@/assets/images/networks/circle/veri.svg';
import vet from '@/assets/images/networks/circle/vet.svg';
import via from '@/assets/images/networks/circle/via.svg';
import vib from '@/assets/images/networks/circle/vib.svg';
import vibe from '@/assets/images/networks/circle/vibe.svg';
import vivo from '@/assets/images/networks/circle/vivo.svg';
import vrc from '@/assets/images/networks/circle/vrc.svg';
import vrsc from '@/assets/images/networks/circle/vrsc.svg';
import vtc from '@/assets/images/networks/circle/vtc.svg';
import vtho from '@/assets/images/networks/circle/vtho.svg';
import wabi from '@/assets/images/networks/circle/wabi.svg';
import wan from '@/assets/images/networks/circle/wan.svg';
import waves from '@/assets/images/networks/circle/waves.svg';
import wax from '@/assets/images/networks/circle/wax.svg';
import wgr from '@/assets/images/networks/circle/wgr.svg';
import wicc from '@/assets/images/networks/circle/wicc.svg';
import wings from '@/assets/images/networks/circle/wings.svg';
import wpr from '@/assets/images/networks/circle/wpr.svg';
import wtc from '@/assets/images/networks/circle/wtc.svg';
import x from '@/assets/images/networks/circle/x.svg';
import xas from '@/assets/images/networks/circle/xas.svg';
import xbc from '@/assets/images/networks/circle/xbc.svg';
import xby from '@/assets/images/networks/circle/xby.svg';
import xcp from '@/assets/images/networks/circle/xcp.svg';
import xdn from '@/assets/images/networks/circle/xdn.svg';
import xem from '@/assets/images/networks/circle/xem.svg';
import xin from '@/assets/images/networks/circle/xin.svg';
import xlm from '@/assets/images/networks/circle/xlm.svg';
import xmcc from '@/assets/images/networks/circle/xmcc.svg';
import xmg from '@/assets/images/networks/circle/xmg.svg';
import xmo from '@/assets/images/networks/circle/xmo.svg';
import xmr from '@/assets/images/networks/circle/xmr.svg';
import xmy from '@/assets/images/networks/circle/xmy.svg';
import xp from '@/assets/images/networks/circle/xp.svg';
import xpa from '@/assets/images/networks/circle/xpa.svg';
import xpm from '@/assets/images/networks/circle/xpm.svg';
import xrp from '@/assets/images/networks/circle/xrp.svg';
import xsg from '@/assets/images/networks/circle/xsg.svg';
import xtz from '@/assets/images/networks/circle/xtz.svg';
import xuc from '@/assets/images/networks/circle/xuc.svg';
import xvc from '@/assets/images/networks/circle/xvc.svg';
import xvg from '@/assets/images/networks/circle/xvg.svg';
import xzc from '@/assets/images/networks/circle/xzc.svg';
import yoyow from '@/assets/images/networks/circle/yoyow.svg';
import zcl from '@/assets/images/networks/circle/zcl.svg';
import zec from '@/assets/images/networks/circle/zec.svg';
import zel from '@/assets/images/networks/circle/zel.svg';
import zen from '@/assets/images/networks/circle/zen.svg';
import zest from '@/assets/images/networks/circle/zest.svg';
import zil from '@/assets/images/networks/circle/zil.svg';
import zilla from '@/assets/images/networks/circle/zilla.svg';
import zrx from '@/assets/images/networks/circle/zrx.svg';

import notAvailable from '@/assets/images/networks/not-available.svg';

export default {
  components: {},
  props: {
    crypto: {
      type: String,
      default: ''
    }
  },
  data() {
    return {
      coins: {
        $pac: $pac,
        toGive: toGive,
        abt: abt,
        act: act,
        actn: actn,
        ada: ada,
        add: add,
        adx: adx,
        ae: ae,
        aeon: aeon,
        aeur: aeur,
        agi: agi,
        agrs: agrs,
        aion: aion,
        amb: amb,
        amp: amp,
        ant: ant,
        apex: apex,
        appc: appc,
        ardr: ardr,
        arg: arg,
        ark: ark,
        arn: arn,
        ary: ary,
        ast: ast,
        atm: atm,
        audr: audr,
        auto: auto,
        aywa: aywa,
        bab: bab,
        bat: bat,
        bay: bay,
        bcbc: bcbc,
        bcc: bcc,
        bcd: bcd,
        bch: bch,
        bcio: bcio,
        bcn: bcn,
        bco: bco,
        bcpt: bcpt,
        bdl: bdl,
        beam: beam,
        bela: bela,
        bix: bix,
        blcn: blcn,
        blk: blk,
        block: block,
        blz: blz,
        bnb: bnb,
        bnt: bnt,
        bnty: bnty,
        booty: booty,
        bos: bos,
        bpt: bpt,
        bq: bq,
        brd: brd,
        bsd: bsd,
        bsv: bsv,
        btc: btc,
        btcd: btcd,
        btch: btch,
        btcp: btcp,
        btcz: btcz,
        btdx: btdx,
        btg: btg,
        btm: btm,
        bts: bts,
        btt: btt,
        btx: btx,
        burst: burst,
        call: call,
        cc: cc,
        cdn: cdn,
        cdt: cdt,
        cenz: cenz,
        chain: chain,
        chat: chat,
        chips: chips,
        cix: cix,
        clam: clam,
        cloak: cloak,
        cmm: cmm,
        cmt: cmt,
        cnd: cnd,
        cnx: cnx,
        cny: cny,
        cob: cob,
        colx: colx,
        coqui: coqui,
        cred: cred,
        crpt: crpt,
        crw: crw,
        cs: cs,
        ctr: ctr,
        ctxc: ctxc,
        cvc: cvc,
        dai: dai,
        dash: dash,
        dat: dat,
        data: data,
        dbc: dbc,
        dcn: dcn,
        dcr: dcr,
        deez: deez,
        dent: dent,
        dew: dew,
        dgb: dgb,
        dgd: dgd,
        dlt: dlt,
        dnr: dnr,
        dnt: dnt,
        dock: dock,
        doge: doge,
        drgn: drgn,
        drop: drop,
        dta: dta,
        dth: dth,
        dtr: dtr,
        ebst: ebst,
        eca: eca,
        edg: edg,
        edo: edo,
        edoge: edoge,
        ela: ela,
        elf: elf,
        elix: elix,
        ella: ella,
        emc: emc,
        emc2: emc2,
        eng: eng,
        enj: enj,
        entrp: entrp,
        eon: eon,
        eop: eop,
        eos: eos,
        eqli: eqli,
        equa: equa,
        etc: etc,
        eth: eth,
        ethos: ethos,
        etn: etn,
        etp: etp,
        eur: eur,
        evx: evx,
        exmo: exmo,
        exp: exp,
        fair: fair,
        fct: fct,
        fil: fil,
        fjc: fjc,
        fldc: fldc,
        flo: flo,
        fsn: fsn,
        ftc: ftc,
        fuel: fuel,
        fun: fun,
        game: game,
        gas: gas,
        gbp: gbp,
        gbx: gbx,
        gbyte: gbyte,
        generic: generic,
        gin: gin,
        glxt: glxt,
        gmr: gmr,
        gno: gno,
        gnt: gnt,
        gold: gold,
        grc: grc,
        grin: grin,
        grs: grs,
        gsc: gsc,
        gto: gto,
        gup: gup,
        gusd: gusd,
        gvt: gvt,
        gxs: gxs,
        gzr: gzr,
        hight: hight,
        hodl: hodl,
        hot: hot,
        hpb: hpb,
        hsr: hsr,
        ht: ht,
        html: html,
        huc: huc,
        hush: hush,
        icn: icn,
        icx: icx,
        ignis: ignis,
        ilk: ilk,
        ink: ink,
        ins: ins,
        ion: ion,
        iop: iop,
        iost: iost,
        iotx: iotx,
        iq: iq,
        itc: itc,
        jnt: jnt,
        jpy: jpy,
        kcs: kcs,
        kin: kin,
        kmd: kmd,
        knc: knc,
        krb: krb,
        lbc: lbc,
        lend: lend,
        link: link,
        lkk: lkk,
        loom: loom,
        lpt: lpt,
        lrc: lrc,
        lsk: lsk,
        ltc: ltc,
        lun: lun,
        maid: maid,
        mana: mana,
        mcap: mcap,
        mco: mco,
        mda: mda,
        mds: mds,
        med: med,
        meetone: meetone,
        miota: miota,
        mith: mith,
        mkr: mkr,
        mln: mln,
        mnx: mnx,
        mnz: mnz,
        moac: moac,
        mod: mod,
        mona: mona,
        msr: msr,
        mth: mth,
        mtl: mtl,
        music: music,
        mzc: mzc,
        nano: nano,
        nas: nas,
        nav: nav,
        ncash: ncash,
        ndz: ndz,
        nebl: nebl,
        neo: neo,
        neos: neos,
        neu: neu,
        nexo: nexo,
        ngc: ngc,
        nio: nio,
        nlc2: nlc2,
        nlg: nlg,
        nmc: nmc,
        npxs: npxs,
        nuls: nuls,
        nxs: nxs,
        nxt: nxt,
        oax: oax,
        ok: ok,
        omg: omg,
        omni: omni,
        ong: ong,
        ont: ont,
        oot: oot,
        ost: ost,
        ox: ox,
        part: part,
        pasc: pasc,
        pasl: pasl,
        pax: pax,
        pay: pay,
        payx: payx,
        pink: pink,
        pirl: pirl,
        pivx: pivx,
        plr: plr,
        poa: poa,
        poe: poe,
        polis: polis,
        poly: poly,
        pot: pot,
        powr: powr,
        ppc: ppc,
        ppp: ppp,
        ppt: ppt,
        pre: pre,
        prl: prl,
        pungo: pungo,
        pura: pura,
        qash: qash,
        qiwi: qiwi,
        qlc: qlc,
        qrl: qrl,
        qsp: qsp,
        qtum: qtum,
        r: r,
        rads: rads,
        rap: rap,
        rcn: rcn,
        rdd: rdd,
        rdn: rdn,
        rep: rep,
        req: req,
        rhoc: rhoc,
        ric: ric,
        rise: rise,
        rlc: rlc,
        rpx: rpx,
        rub: rub,
        rvn: rvn,
        ryo: ryo,
        safe: safe,
        salt: salt,
        san: san,
        sbd: sbd,
        sberbank: sberbank,
        sc: sc,
        shift: shift,
        sib: sib,
        sky: sky,
        slr: slr,
        sls: sls,
        smart: smart,
        sngls: sngls,
        snm: snm,
        snt: snt,
        soc: soc,
        spank: spank,
        sphtx: sphtx,
        srn: srn,
        stak: stak,
        start: start,
        steem: steem,
        storj: storj,
        storm: storm,
        stq: stq,
        strat: strat,
        sub: sub,
        sumo: sumo,
        sys: sys,
        taas: taas,
        tau: tau,
        tbx: tbx,
        tel: tel,
        ten: ten,
        tern: tern,
        tghc: tghc,
        theta: theta,
        tix: tix,
        tkn: tkn,
        tks: tks,
        tnb: tnb,
        tnc: tnc,
        tnt: tnt,
        tomo: tomo,
        tpay: tpay,
        trig: trig,
        trtl: trtl,
        trx: trx,
        tusd: tusd,
        tzc: tzc,
        ubq: ubq,
        unity: unity,
        usd: usd,
        usdc: usdc,
        usdt: usdt,
        utk: utk,
        veri: veri,
        vet: vet,
        via: via,
        vib: vib,
        vibe: vibe,
        vivo: vivo,
        vrc: vrc,
        vrsc: vrsc,
        vtc: vtc,
        vtho: vtho,
        wabi: wabi,
        wan: wan,
        waves: waves,
        wax: wax,
        wgr: wgr,
        wicc: wicc,
        wings: wings,
        wpr: wpr,
        wtc: wtc,
        x: x,
        xas: xas,
        xbc: xbc,
        xby: xby,
        xcp: xcp,
        xdn: xdn,
        xem: xem,
        xin: xin,
        xlm: xlm,
        xmcc: xmcc,
        xmg: xmg,
        xmo: xmo,
        xmr: xmr,
        xmy: xmy,
        xp: xp,
        xpa: xpa,
        xpm: xpm,
        xrp: xrp,
        xsg: xsg,
        xtz: xtz,
        xuc: xuc,
        xvc: xvc,
        xvg: xvg,
        xzc: xzc,
        yoyow: yoyow,
        zcl: zcl,
        zec: zec,
        zel: zel,
        zen: zen,
        zest: zest,
        zil: zil,
        zilla: zilla,
        zrx: zrx
      },
      na: notAvailable,
      selectedCoin: null
    };
  },
  mounted() {
    this.iconSelector();
  },
  methods: {
    iconSelector() {
      switch (this.crypto.toLowerCase()) {
        case '$pac':
          this.selectedCoin = this.coins.$pac;
          break;

        case 'toGive':
          this.selectedCoin = this.coins.toGive;
          break;
        case 'abt':
          this.selectedCoin = this.coins.abt;
          break;
        case 'act':
          this.selectedCoin = this.coins.act;
          break;
        case 'actn':
          this.selectedCoin = this.coins.actn;
          break;
        case 'ada':
          this.selectedCoin = this.coins.ada;
          break;
        case 'add':
          this.selectedCoin = this.coins.add;
          break;
        case 'adx':
          this.selectedCoin = this.coins.adx;
          break;
        case 'ae':
          this.selectedCoin = this.coins.ae;
          break;
        case 'aeon':
          this.selectedCoin = this.coins.aeon;
          break;
        case 'aeur':
          this.selectedCoin = this.coins.aeur;
          break;
        case 'agi':
          this.selectedCoin = this.coins.agi;
          break;
        case 'agrs':
          this.selectedCoin = this.coins.agrs;
          break;
        case 'aion':
          this.selectedCoin = this.coins.aion;
          break;
        case 'amb':
          this.selectedCoin = this.coins.amb;
          break;
        case 'amp':
          this.selectedCoin = this.coins.amp;
          break;
        case 'ant':
          this.selectedCoin = this.coins.ant;
          break;
        case 'apex':
          this.selectedCoin = this.coins.apex;
          break;
        case 'appc':
          this.selectedCoin = this.coins.appc;
          break;
        case 'ardr':
          this.selectedCoin = this.coins.ardr;
          break;
        case 'arg':
          this.selectedCoin = this.coins.arg;
          break;
        case 'ark':
          this.selectedCoin = this.coins.ark;
          break;
        case 'arn':
          this.selectedCoin = this.coins.arn;
          break;
        case 'ary':
          this.selectedCoin = this.coins.ary;
          break;
        case 'ast':
          this.selectedCoin = this.coins.ast;
          break;
        case 'atm':
          this.selectedCoin = this.coins.atm;
          break;
        case 'audr':
          this.selectedCoin = this.coins.audr;
          break;

        case 'auto':
          this.selectedCoin = this.coins.auto;
          break;
        case 'aywa':
          this.selectedCoin = this.coins.aywa;
          break;
        case 'bab':
          this.selectedCoin = this.coins.bab;
          break;
        case 'bat':
          this.selectedCoin = this.coins.bat;
          break;
        case 'bay':
          this.selectedCoin = this.coins.bay;
          break;
        case 'bcbc':
          this.selectedCoin = this.coins.bcbc;
          break;
        case 'bcc':
          this.selectedCoin = this.coins.bcc;
          break;
        case 'bcd':
          this.selectedCoin = this.coins.bcd;
          break;
        case 'bch':
          this.selectedCoin = this.coins.bch;
          break;
        case 'bcio':
          this.selectedCoin = this.coins.bcio;
          break;
        case 'bcn':
          this.selectedCoin = this.coins.bcn;
          break;
        case 'bco':
          this.selectedCoin = this.coins.bco;
          break;
        case 'bcpt':
          this.selectedCoin = this.coins.bcpt;
          break;
        case 'bdl':
          this.selectedCoin = this.coins.bdl;
          break;
        case 'beam':
          this.selectedCoin = this.coins.beam;
          break;
        case 'bela':
          this.selectedCoin = this.coins.bela;
          break;
        case 'bix':
          this.selectedCoin = this.coins.bix;
          break;
        case 'blcn':
          this.selectedCoin = this.coins.blcn;
          break;
        case 'blk':
          this.selectedCoin = this.coins.blk;
          break;
        case 'block':
          this.selectedCoin = this.coins.block;
          break;
        case 'blz':
          this.selectedCoin = this.coins.blz;
          break;
        case 'bnb':
          this.selectedCoin = this.coins.bnb;
          break;
        case 'bnt':
          this.selectedCoin = this.coins.bnt;
          break;
        case 'bnty':
          this.selectedCoin = this.coins.bnty;
          break;
        case 'booty':
          this.selectedCoin = this.coins.booty;
          break;
        case 'bos':
          this.selectedCoin = this.coins.bos;
          break;
        case 'bpt':
          this.selectedCoin = this.coins.bpt;
          break;
        case 'bq':
          this.selectedCoin = this.coins.bq;
          break;
        case 'brd':
          this.selectedCoin = this.coins.brd;
          break;
        case 'bsd':
          this.selectedCoin = this.coins.bsd;
          break;
        case 'bsv':
          this.selectedCoin = this.coins.bsv;
          break;
        case 'btc':
          this.selectedCoin = this.coins.btc;
          break;
        case 'btcd':
          this.selectedCoin = this.coins.btcd;
          break;
        case 'btch':
          this.selectedCoin = this.coins.btch;
          break;
        case 'btcp':
          this.selectedCoin = this.coins.btcp;
          break;
        case 'btcz':
          this.selectedCoin = this.coins.btcz;
          break;
        case 'btdx':
          this.selectedCoin = this.coins.btdx;
          break;
        case 'btg':
          this.selectedCoin = this.coins.btg;
          break;
        case 'btm':
          this.selectedCoin = this.coins.btm;
          break;
        case 'bts':
          this.selectedCoin = this.coins.bts;
          break;
        case 'btt':
          this.selectedCoin = this.coins.btt;
          break;
        case 'btx':
          this.selectedCoin = this.coins.btx;
          break;
        case 'burst':
          this.selectedCoin = this.coins.burst;
          break;
        case 'call':
          this.selectedCoin = this.coins.call;
          break;
        case 'cc':
          this.selectedCoin = this.coins.cc;
          break;
        case 'cdn':
          this.selectedCoin = this.coins.cdn;
          break;
        case 'cdt':
          this.selectedCoin = this.coins.cdt;
          break;
        case 'cenz':
          this.selectedCoin = this.coins.cenz;
          break;
        case 'chain':
          this.selectedCoin = this.coins.chain;
          break;
        case 'chat':
          this.selectedCoin = this.coins.chat;
          break;
        case 'chips':
          this.selectedCoin = this.coins.chips;
          break;
        case 'cix':
          this.selectedCoin = this.coins.cix;
          break;
        case 'clam':
          this.selectedCoin = this.coins.clam;
          break;
        case 'cloak':
          this.selectedCoin = this.coins.cloak;
          break;
        case 'cmm':
          this.selectedCoin = this.coins.cmm;
          break;
        case 'cmt':
          this.selectedCoin = this.coins.cmt;
          break;
        case 'cnd':
          this.selectedCoin = this.coins.cnd;
          break;
        case 'cnx':
          this.selectedCoin = this.coins.cnx;
          break;
        case 'cny':
          this.selectedCoin = this.coins.cny;
          break;
        case 'cob':
          this.selectedCoin = this.coins.cob;
          break;
        case 'colx':
          this.selectedCoin = this.coins.colx;
          break;
        case 'coqui':
          this.selectedCoin = this.coins.coqui;
          break;
        case 'cred':
          this.selectedCoin = this.coins.cred;
          break;
        case 'crpt':
          this.selectedCoin = this.coins.crpt;
          break;
        case 'crw':
          this.selectedCoin = this.coins.crw;
          break;
        case 'cs':
          this.selectedCoin = this.coins.cs;
          break;
        case 'ctr':
          this.selectedCoin = this.coins.ctr;
          break;
        case 'ctxc':
          this.selectedCoin = this.coins.ctxc;
          break;
        case 'cvc':
          this.selectedCoin = this.coins.cvc;
          break;
        case 'dai':
          this.selectedCoin = this.coins.dai;
          break;
        case 'dash':
          this.selectedCoin = this.coins.dash;
          break;
        case 'dat':
          this.selectedCoin = this.coins.dat;
          break;
        case 'data':
          this.selectedCoin = this.coins.data;
          break;
        case 'dbc':
          this.selectedCoin = this.coins.dbc;
          break;
        case 'dcn':
          this.selectedCoin = this.coins.dcn;
          break;
        case 'dcr':
          this.selectedCoin = this.coins.dcr;
          break;
        case 'deez':
          this.selectedCoin = this.coins.deez;
          break;
        case 'dent':
          this.selectedCoin = this.coins.dent;
          break;
        case 'dew':
          this.selectedCoin = this.coins.dew;
          break;
        case 'dgb':
          this.selectedCoin = this.coins.dgb;
          break;
        case 'dgd':
          this.selectedCoin = this.coins.dgd;
          break;
        case 'dlt':
          this.selectedCoin = this.coins.dlt;
          break;
        case 'dnr':
          this.selectedCoin = this.coins.dnr;
          break;
        case 'dnt':
          this.selectedCoin = this.coins.dnt;
          break;
        case 'dock':
          this.selectedCoin = this.coins.dock;
          break;
        case 'doge':
          this.selectedCoin = this.coins.doge;
          break;
        case 'drgn':
          this.selectedCoin = this.coins.drgn;
          break;
        case 'drop':
          this.selectedCoin = this.coins.drop;
          break;
        case 'dta':
          this.selectedCoin = this.coins.dta;
          break;
        case 'dth':
          this.selectedCoin = this.coins.dth;
          break;
        case 'dtr':
          this.selectedCoin = this.coins.dtr;
          break;
        case 'ebst':
          this.selectedCoin = this.coins.ebst;
          break;
        case 'eca':
          this.selectedCoin = this.coins.eca;
          break;
        case 'edg':
          this.selectedCoin = this.coins.edg;
          break;
        case 'edo':
          this.selectedCoin = this.coins.edo;
          break;
        case 'edoge':
          this.selectedCoin = this.coins.edoge;
          break;
        case 'ela':
          this.selectedCoin = this.coins.ela;
          break;
        case 'elf':
          this.selectedCoin = this.coins.elf;
          break;
        case 'elix':
          this.selectedCoin = this.coins.elix;
          break;
        case 'ella':
          this.selectedCoin = this.coins.ella;
          break;
        case 'emc':
          this.selectedCoin = this.coins.emc;
          break;
        case 'emc2':
          this.selectedCoin = this.coins.emc2;
          break;
        case 'eng':
          this.selectedCoin = this.coins.eng;
          break;
        case 'enj':
          this.selectedCoin = this.coins.enj;
          break;
        case 'entrp':
          this.selectedCoin = this.coins.entrp;
          break;
        case 'eon':
          this.selectedCoin = this.coins.eon;
          break;
        case 'eop':
          this.selectedCoin = this.coins.eop;
          break;
        case 'eos':
          this.selectedCoin = this.coins.eos;
          break;
        case 'eqli':
          this.selectedCoin = this.coins.eqli;
          break;
        case 'equa':
          this.selectedCoin = this.coins.equa;
          break;
        case 'etc':
          this.selectedCoin = this.coins.etc;
          break;
        case 'eth':
          this.selectedCoin = this.coins.eth;
          break;
        case 'ethos':
          this.selectedCoin = this.coins.ethos;
          break;
        case 'etn':
          this.selectedCoin = this.coins.etn;
          break;
        case 'etp':
          this.selectedCoin = this.coins.etp;
          break;
        case 'eur':
          this.selectedCoin = this.coins.eur;
          break;
        case 'evx':
          this.selectedCoin = this.coins.evx;
          break;
        case 'exmo':
          this.selectedCoin = this.coins.exmo;
          break;
        case 'exp':
          this.selectedCoin = this.coins.exp;
          break;
        case 'fair':
          this.selectedCoin = this.coins.fair;
          break;
        case 'fct':
          this.selectedCoin = this.coins.fct;
          break;
        case 'fil':
          this.selectedCoin = this.coins.fil;
          break;
        case 'fjc':
          this.selectedCoin = this.coins.fjc;
          break;
        case 'fldc':
          this.selectedCoin = this.coins.fldc;
          break;
        case 'flo':
          this.selectedCoin = this.coins.flo;
          break;
        case 'fsn':
          this.selectedCoin = this.coins.fsn;
          break;
        case 'ftc':
          this.selectedCoin = this.coins.ftc;
          break;
        case 'fuel':
          this.selectedCoin = this.coins.fuel;
          break;
        case 'fun':
          this.selectedCoin = this.coins.fun;
          break;
        case 'game':
          this.selectedCoin = this.coins.game;
          break;
        case 'gas':
          this.selectedCoin = this.coins.gas;
          break;
        case 'gbp':
          this.selectedCoin = this.coins.gbp;
          break;
        case 'gbx':
          this.selectedCoin = this.coins.gbx;
          break;
        case 'gbyte':
          this.selectedCoin = this.coins.gbyte;
          break;
        case 'generic':
          this.selectedCoin = this.coins.generic;
          break;
        case 'gin':
          this.selectedCoin = this.coins.gin;
          break;
        case 'glxt':
          this.selectedCoin = this.coins.glxt;
          break;
        case 'gmr':
          this.selectedCoin = this.coins.gmr;
          break;
        case 'gno':
          this.selectedCoin = this.coins.gno;
          break;
        case 'gnt':
          this.selectedCoin = this.coins.gnt;
          break;
        case 'gold':
          this.selectedCoin = this.coins.gold;
          break;
        case 'grc':
          this.selectedCoin = this.coins.grc;
          break;
        case 'grin':
          this.selectedCoin = this.coins.grin;
          break;
        case 'grs':
          this.selectedCoin = this.coins.grs;
          break;
        case 'gsc':
          this.selectedCoin = this.coins.gsc;
          break;
        case 'gto':
          this.selectedCoin = this.coins.gto;
          break;
        case 'gup':
          this.selectedCoin = this.coins.gup;
          break;
        case 'gusd':
          this.selectedCoin = this.coins.gusd;
          break;
        case 'gvt':
          this.selectedCoin = this.coins.gvt;
          break;
        case 'gxs':
          this.selectedCoin = this.coins.gxs;
          break;
        case 'gzr':
          this.selectedCoin = this.coins.gzr;
          break;
        case 'hight':
          this.selectedCoin = this.coins.hight;
          break;
        case 'hodl':
          this.selectedCoin = this.coins.hodl;
          break;
        case 'hot':
          this.selectedCoin = this.coins.hot;
          break;
        case 'hpb':
          this.selectedCoin = this.coins.hpb;
          break;
        case 'hsr':
          this.selectedCoin = this.coins.hsr;
          break;
        case 'ht':
          this.selectedCoin = this.coins.ht;
          break;
        case 'html':
          this.selectedCoin = this.coins.html;
          break;
        case 'huc':
          this.selectedCoin = this.coins.huc;
          break;
        case 'hush':
          this.selectedCoin = this.coins.hush;
          break;
        case 'icn':
          this.selectedCoin = this.coins.icn;
          break;
        case 'icx':
          this.selectedCoin = this.coins.icx;
          break;
        case 'ignis':
          this.selectedCoin = this.coins.ignis;
          break;
        case 'ilk':
          this.selectedCoin = this.coins.ilk;
          break;
        case 'ink':
          this.selectedCoin = this.coins.ink;
          break;
        case 'ins':
          this.selectedCoin = this.coins.ins;
          break;
        case 'ion':
          this.selectedCoin = this.coins.ion;
          break;
        case 'iop':
          this.selectedCoin = this.coins.iop;
          break;
        case 'iost':
          this.selectedCoin = this.coins.iost;
          break;
        case 'iotx':
          this.selectedCoin = this.coins.iotx;
          break;
        case 'iq':
          this.selectedCoin = this.coins.iq;
          break;
        case 'itc':
          this.selectedCoin = this.coins.itc;
          break;
        case 'jnt':
          this.selectedCoin = this.coins.jnt;
          break;
        case 'jpy':
          this.selectedCoin = this.coins.jpy;
          break;
        case 'kcs':
          this.selectedCoin = this.coins.kcs;
          break;
        case 'kin':
          this.selectedCoin = this.coins.kin;
          break;
        case 'kmd':
          this.selectedCoin = this.coins.kmd;
          break;
        case 'knc':
          this.selectedCoin = this.coins.knc;
          break;
        case 'krb':
          this.selectedCoin = this.coins.krb;
          break;
        case 'lbc':
          this.selectedCoin = this.coins.lbc;
          break;
        case 'lend':
          this.selectedCoin = this.coins.lend;
          break;
        case 'link':
          this.selectedCoin = this.coins.link;
          break;
        case 'lkk':
          this.selectedCoin = this.coins.lkk;
          break;
        case 'loom':
          this.selectedCoin = this.coins.loom;
          break;
        case 'lpt':
          this.selectedCoin = this.coins.lpt;
          break;
        case 'lrc':
          this.selectedCoin = this.coins.lrc;
          break;
        case 'lsk':
          this.selectedCoin = this.coins.lsk;
          break;
        case 'ltc':
          this.selectedCoin = this.coins.ltc;
          break;
        case 'lun':
          this.selectedCoin = this.coins.lun;
          break;
        case 'maid':
          this.selectedCoin = this.coins.maid;
          break;
        case 'mana':
          this.selectedCoin = this.coins.mana;
          break;
        case 'mcap':
          this.selectedCoin = this.coins.mcap;
          break;
        case 'mco':
          this.selectedCoin = this.coins.mco;
          break;
        case 'mda':
          this.selectedCoin = this.coins.mda;
          break;
        case 'mds':
          this.selectedCoin = this.coins.mds;
          break;
        case 'med':
          this.selectedCoin = this.coins.med;
          break;
        case 'meetone':
          this.selectedCoin = this.coins.meetone;
          break;
        case 'miota':
          this.selectedCoin = this.coins.miota;
          break;
        case 'mith':
          this.selectedCoin = this.coins.mith;
          break;
        case 'mkr':
          this.selectedCoin = this.coins.mkr;
          break;
        case 'mln':
          this.selectedCoin = this.coins.mln;
          break;
        case 'mnx':
          this.selectedCoin = this.coins.mnx;
          break;
        case 'mnz':
          this.selectedCoin = this.coins.mnz;
          break;
        case 'moac':
          this.selectedCoin = this.coins.moac;
          break;
        case 'mod':
          this.selectedCoin = this.coins.mod;
          break;
        case 'mona':
          this.selectedCoin = this.coins.mona;
          break;
        case 'msr':
          this.selectedCoin = this.coins.msr;
          break;
        case 'mth':
          this.selectedCoin = this.coins.mth;
          break;
        case 'mtl':
          this.selectedCoin = this.coins.mtl;
          break;
        case 'music':
          this.selectedCoin = this.coins.music;
          break;
        case 'mzc':
          this.selectedCoin = this.coins.mzc;
          break;
        case 'nano':
          this.selectedCoin = this.coins.nano;
          break;
        case 'nas':
          this.selectedCoin = this.coins.nas;
          break;
        case 'nav':
          this.selectedCoin = this.coins.nav;
          break;
        case 'ncash':
          this.selectedCoin = this.coins.ncash;
          break;
        case 'ndz':
          this.selectedCoin = this.coins.ndz;
          break;
        case 'nebl':
          this.selectedCoin = this.coins.nebl;
          break;
        case 'neo':
          this.selectedCoin = this.coins.neo;
          break;
        case 'neos':
          this.selectedCoin = this.coins.neos;
          break;
        case 'neu':
          this.selectedCoin = this.coins.neu;
          break;
        case 'nexo':
          this.selectedCoin = this.coins.nexo;
          break;
        case 'ngc':
          this.selectedCoin = this.coins.ngc;
          break;
        case 'nio':
          this.selectedCoin = this.coins.nio;
          break;
        case 'nlc2':
          this.selectedCoin = this.coins.nlc2;
          break;
        case 'nlg':
          this.selectedCoin = this.coins.nlg;
          break;
        case 'nmc':
          this.selectedCoin = this.coins.nmc;
          break;
        case 'npxs':
          this.selectedCoin = this.coins.npxs;
          break;
        case 'nuls':
          this.selectedCoin = this.coins.nuls;
          break;
        case 'nxs':
          this.selectedCoin = this.coins.nxs;
          break;
        case 'nxt':
          this.selectedCoin = this.coins.nxt;
          break;
        case 'oax':
          this.selectedCoin = this.coins.oax;
          break;
        case 'ok':
          this.selectedCoin = this.coins.ok;
          break;
        case 'omg':
          this.selectedCoin = this.coins.omg;
          break;
        case 'omni':
          this.selectedCoin = this.coins.omni;
          break;
        case 'ong':
          this.selectedCoin = this.coins.ong;
          break;
        case 'ont':
          this.selectedCoin = this.coins.ont;
          break;
        case 'oot':
          this.selectedCoin = this.coins.oot;
          break;
        case 'ost':
          this.selectedCoin = this.coins.ost;
          break;
        case 'ox':
          this.selectedCoin = this.coins.ox;
          break;
        case 'part':
          this.selectedCoin = this.coins.part;
          break;
        case 'pasc':
          this.selectedCoin = this.coins.pasc;
          break;
        case 'pasl':
          this.selectedCoin = this.coins.pasl;
          break;
        case 'pax':
          this.selectedCoin = this.coins.pax;
          break;
        case 'pay':
          this.selectedCoin = this.coins.pay;
          break;
        case 'payx':
          this.selectedCoin = this.coins.payx;
          break;
        case 'pink':
          this.selectedCoin = this.coins.pink;
          break;
        case 'pirl':
          this.selectedCoin = this.coins.pirl;
          break;
        case 'pivx':
          this.selectedCoin = this.coins.pivx;
          break;
        case 'plr':
          this.selectedCoin = this.coins.plr;
          break;
        case 'poa':
          this.selectedCoin = this.coins.poa;
          break;
        case 'poe':
          this.selectedCoin = this.coins.poe;
          break;
        case 'polis':
          this.selectedCoin = this.coins.polis;
          break;
        case 'poly':
          this.selectedCoin = this.coins.poly;
          break;
        case 'pot':
          this.selectedCoin = this.coins.pot;
          break;
        case 'powr':
          this.selectedCoin = this.coins.powr;
          break;
        case 'ppc':
          this.selectedCoin = this.coins.ppc;
          break;
        case 'ppp':
          this.selectedCoin = this.coins.ppp;
          break;
        case 'ppt':
          this.selectedCoin = this.coins.ppt;
          break;
        case 'pre':
          this.selectedCoin = this.coins.pre;
          break;
        case 'prl':
          this.selectedCoin = this.coins.prl;
          break;
        case 'pungo':
          this.selectedCoin = this.coins.pungo;
          break;
        case 'pura':
          this.selectedCoin = this.coins.pura;
          break;
        case 'qash':
          this.selectedCoin = this.coins.qash;
          break;
        case 'qiwi':
          this.selectedCoin = this.coins.qiwi;
          break;
        case 'qlc':
          this.selectedCoin = this.coins.qlc;
          break;
        case 'qrl':
          this.selectedCoin = this.coins.qrl;
          break;
        case 'qsp':
          this.selectedCoin = this.coins.qsp;
          break;
        case 'qtum':
          this.selectedCoin = this.coins.qtum;
          break;
        case 'r':
          this.selectedCoin = this.coins.r;
          break;
        case 'rads':
          this.selectedCoin = this.coins.rads;
          break;
        case 'rap':
          this.selectedCoin = this.coins.rap;
          break;
        case 'rcn':
          this.selectedCoin = this.coins.rcn;
          break;
        case 'rdd':
          this.selectedCoin = this.coins.rdd;
          break;
        case 'rdn':
          this.selectedCoin = this.coins.rdn;
          break;
        case 'rep':
          this.selectedCoin = this.coins.rep;
          break;
        case 'req':
          this.selectedCoin = this.coins.req;
          break;
        case 'rhoc':
          this.selectedCoin = this.coins.rhoc;
          break;
        case 'ric':
          this.selectedCoin = this.coins.ric;
          break;
        case 'rise':
          this.selectedCoin = this.coins.rise;
          break;
        case 'rlc':
          this.selectedCoin = this.coins.rlc;
          break;
        case 'rpx':
          this.selectedCoin = this.coins.rpx;
          break;
        case 'rub':
          this.selectedCoin = this.coins.rub;
          break;
        case 'rvn':
          this.selectedCoin = this.coins.rvn;
          break;
        case 'ryo':
          this.selectedCoin = this.coins.ryo;
          break;
        case 'safe':
          this.selectedCoin = this.coins.safe;
          break;
        case 'salt':
          this.selectedCoin = this.coins.salt;
          break;
        case 'san':
          this.selectedCoin = this.coins.san;
          break;
        case 'sbd':
          this.selectedCoin = this.coins.sbd;
          break;
        case 'sberbank':
          this.selectedCoin = this.coins.sberbank;
          break;
        case 'sc':
          this.selectedCoin = this.coins.sc;
          break;
        case 'shift':
          this.selectedCoin = this.coins.shift;
          break;
        case 'sib':
          this.selectedCoin = this.coins.sib;
          break;
        case 'sky':
          this.selectedCoin = this.coins.sky;
          break;
        case 'slr':
          this.selectedCoin = this.coins.slr;
          break;
        case 'sls':
          this.selectedCoin = this.coins.sls;
          break;
        case 'smart':
          this.selectedCoin = this.coins.smart;
          break;
        case 'sngls':
          this.selectedCoin = this.coins.sngls;
          break;
        case 'snm':
          this.selectedCoin = this.coins.snm;
          break;
        case 'snt':
          this.selectedCoin = this.coins.snt;
          break;
        case 'soc':
          this.selectedCoin = this.coins.soc;
          break;
        case 'spank':
          this.selectedCoin = this.coins.spank;
          break;
        case 'sphtx':
          this.selectedCoin = this.coins.sphtx;
          break;
        case 'srn':
          this.selectedCoin = this.coins.srn;
          break;
        case 'stak':
          this.selectedCoin = this.coins.stak;
          break;
        case 'start':
          this.selectedCoin = this.coins.start;
          break;
        case 'steem':
          this.selectedCoin = this.coins.steem;
          break;
        case 'storj':
          this.selectedCoin = this.coins.storj;
          break;
        case 'storm':
          this.selectedCoin = this.coins.storm;
          break;
        case 'stq':
          this.selectedCoin = this.coins.stq;
          break;
        case 'strat':
          this.selectedCoin = this.coins.strat;
          break;
        case 'sub':
          this.selectedCoin = this.coins.sub;
          break;
        case 'sumo':
          this.selectedCoin = this.coins.sumo;
          break;
        case 'sys':
          this.selectedCoin = this.coins.sys;
          break;
        case 'taas':
          this.selectedCoin = this.coins.taas;
          break;
        case 'tau':
          this.selectedCoin = this.coins.tau;
          break;
        case 'tbx':
          this.selectedCoin = this.coins.tbx;
          break;
        case 'tel':
          this.selectedCoin = this.coins.tel;
          break;
        case 'ten':
          this.selectedCoin = this.coins.ten;
          break;
        case 'tern':
          this.selectedCoin = this.coins.tern;
          break;
        case 'tghc':
          this.selectedCoin = this.coins.tghc;
          break;
        case 'theta':
          this.selectedCoin = this.coins.theta;
          break;
        case 'tix':
          this.selectedCoin = this.coins.tix;
          break;
        case 'tkn':
          this.selectedCoin = this.coins.tkn;
          break;
        case 'tks':
          this.selectedCoin = this.coins.tks;
          break;
        case 'tnb':
          this.selectedCoin = this.coins.tnb;
          break;
        case 'tnc':
          this.selectedCoin = this.coins.tnc;
          break;
        case 'tnt':
          this.selectedCoin = this.coins.tnt;
          break;
        case 'tomo':
          this.selectedCoin = this.coins.tomo;
          break;
        case 'tpay':
          this.selectedCoin = this.coins.tpay;
          break;
        case 'trig':
          this.selectedCoin = this.coins.trig;
          break;
        case 'trtl':
          this.selectedCoin = this.coins.trtl;
          break;
        case 'trx':
          this.selectedCoin = this.coins.trx;
          break;
        case 'tusd':
          this.selectedCoin = this.coins.tusd;
          break;
        case 'tzc':
          this.selectedCoin = this.coins.tzc;
          break;
        case 'ubq':
          this.selectedCoin = this.coins.ubq;
          break;
        case 'unity':
          this.selectedCoin = this.coins.unity;
          break;
        case 'usd':
          this.selectedCoin = this.coins.usd;
          break;
        case 'usdc':
          this.selectedCoin = this.coins.usdc;
          break;
        case 'usdt':
          this.selectedCoin = this.coins.usdt;
          break;
        case 'utk':
          this.selectedCoin = this.coins.utk;
          break;
        case 'veri':
          this.selectedCoin = this.coins.veri;
          break;
        case 'vet':
          this.selectedCoin = this.coins.vet;
          break;
        case 'via':
          this.selectedCoin = this.coins.via;
          break;
        case 'vib':
          this.selectedCoin = this.coins.vib;
          break;
        case 'vibe':
          this.selectedCoin = this.coins.vibe;
          break;
        case 'vivo':
          this.selectedCoin = this.coins.vivo;
          break;
        case 'vrc':
          this.selectedCoin = this.coins.vrc;
          break;
        case 'vrsc':
          this.selectedCoin = this.coins.vrsc;
          break;
        case 'vtc':
          this.selectedCoin = this.coins.vtc;
          break;
        case 'vtho':
          this.selectedCoin = this.coins.vtho;
          break;
        case 'wabi':
          this.selectedCoin = this.coins.wabi;
          break;
        case 'wan':
          this.selectedCoin = this.coins.wan;
          break;
        case 'waves':
          this.selectedCoin = this.coins.waves;
          break;
        case 'wax':
          this.selectedCoin = this.coins.wax;
          break;
        case 'wgr':
          this.selectedCoin = this.coins.wgr;
          break;
        case 'wicc':
          this.selectedCoin = this.coins.wicc;
          break;
        case 'wings':
          this.selectedCoin = this.coins.wings;
          break;
        case 'wpr':
          this.selectedCoin = this.coins.wpr;
          break;
        case 'wtc':
          this.selectedCoin = this.coins.wtc;
          break;
        case 'x':
          this.selectedCoin = this.coins.x;
          break;
        case 'xas':
          this.selectedCoin = this.coins.xas;
          break;
        case 'xbc':
          this.selectedCoin = this.coins.xbc;
          break;
        case 'xby':
          this.selectedCoin = this.coins.xby;
          break;
        case 'xcp':
          this.selectedCoin = this.coins.xcp;
          break;
        case 'xdn':
          this.selectedCoin = this.coins.xdn;
          break;
        case 'xem':
          this.selectedCoin = this.coins.xem;
          break;
        case 'xin':
          this.selectedCoin = this.coins.xin;
          break;
        case 'xlm':
          this.selectedCoin = this.coins.xlm;
          break;
        case 'xmcc':
          this.selectedCoin = this.coins.xmcc;
          break;
        case 'xmg':
          this.selectedCoin = this.coins.xmg;
          break;
        case 'xmo':
          this.selectedCoin = this.coins.xmo;
          break;
        case 'xmr':
          this.selectedCoin = this.coins.xmr;
          break;
        case 'xmy':
          this.selectedCoin = this.coins.xmy;
          break;
        case 'xp':
          this.selectedCoin = this.coins.xp;
          break;
        case 'xpa':
          this.selectedCoin = this.coins.xpa;
          break;
        case 'xpm':
          this.selectedCoin = this.coins.xpm;
          break;
        case 'xrp':
          this.selectedCoin = this.coins.xrp;
          break;
        case 'xsg':
          this.selectedCoin = this.coins.xsg;
          break;
        case 'xtz':
          this.selectedCoin = this.coins.xtz;
          break;
        case 'xuc':
          this.selectedCoin = this.coins.xuc;
          break;
        case 'xvc':
          this.selectedCoin = this.coins.xvc;
          break;
        case 'xvg':
          this.selectedCoin = this.coins.xvg;
          break;
        case 'xzc':
          this.selectedCoin = this.coins.xzc;
          break;
        case 'yoyow':
          this.selectedCoin = this.coins.yoyow;
          break;
        case 'zcl':
          this.selectedCoin = this.coins.zcl;
          break;
        case 'zec':
          this.selectedCoin = this.coins.zec;
          break;
        case 'zel':
          this.selectedCoin = this.coins.zel;
          break;
        case 'zen':
          this.selectedCoin = this.coins.zen;
          break;
        case 'zest':
          this.selectedCoin = this.coins.zest;
          break;
        case 'zil':
          this.selectedCoin = this.coins.zil;
          break;
        case 'zilla':
          this.selectedCoin = this.coins.zilla;
          break;
        case 'zrx':
          this.selectedCoin = this.coins.zrx;
          break;
        default:
          this.selectedCoin = this.na;
      }
    }
  }
};
</script>

<style lang="scss" scoped>
@import 'CryptoIcons.scss';
</style>
